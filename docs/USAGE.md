# baastream documentation

## 🚀 Usage Examples

### Basic Usage
```bash
# Scan configuration file with free rules
baastream-scan config.json

# Scan with specific rule
baastream-scan -rules AUDIT-001 config.json

# Scan with pro rules
baastream-scan -rules rules/pro config.json
```

### Advanced Usage
```bash
# Filter by severity
baastream-scan -rules rules/pro -severity critical config.json

# Filter by tags
baastream-scan -rules rules/pro -tags hipaa,gdpr config.json

# Multiple output formats
baastream-scan -rules rules/pro -format json config.json
baastream-scan -rules rules/pro -format csv -output report.csv config.json
baastream-scan -rules rules/pro -format pdf -output report.pdf config.json
baastream-scan -rules rules/pro -format summary config.json
```

### Plugin Usage
```bash
# List available plugins
baastream-scan -list-plugins

# Enable specific plugins
baastream-scan -plugins github_actions,terraform config.json

# Scan GitHub Actions workflows
baastream-scan -plugins github_actions .github/workflows/

# Scan Jenkins pipelines
baastream-scan -plugins jenkins Jenkinsfile

# Scan Terraform configurations
baastream-scan -plugins terraform terraform/
```

### Log Scanning
```bash
# Auto-detect log type
baastream-scan -type auto audit.log

# Scan specific log files
baastream-scan -type logs audit.log error.log

# Scan log directory
baastream-scan -type logs logs/

# Scan with specific log rules
baastream-scan -rules LOG-002 -type logs audit.log
```