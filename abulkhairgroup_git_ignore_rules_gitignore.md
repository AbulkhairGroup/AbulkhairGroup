# ==============================================================================
# ABULKHAIR GROUP — .gitignore (Privacy, Private Bootstrap & Workspace Hygiene)
# ==============================================================================

# 1. Private Founder Bootstrap & Internal Workspace Files (NEVER COMMIT)
ABULKHAIR_ECOSYSTEM_AGENT_BOOTSTRAP.md
*agent_bootstrap_hermes*
*bootstrap*private*
*PRIVATE*
private/
internal/
_LOCAL_ONLY/

# 2. Clinical, Patient PII & Private Financial Data (ADC Privacy Lock - ADA-RULE-010)
*patient*
*patients*
*ledger*
*receivables*
*invoice*
*invoices*
*supplier_balances*
*.accdb
*.mdb
*.sqlite
*.sqlite3
*.db
*.csv
*.xlsx
*.xls
!templates/**/*.csv

# 3. Secrets, Credentials & Environment Variables
.env
.env.*
!.env.example
*.pem
*.key
*.p12
*.pfx
credentials.json
token.json
client_secret*.json
secrets/

# 4. AI Agent Local Runtime, Caches & Session Logs
.openclaw/
.hermes/
.claude/
.cursor/
.codex/
*.log
logs/
tmp/
temp/

# 5. Operating System & Editor Artifacts
.DS_Store
.AppleDouble
.LSOverride
Thumbs.db
ehthumbs.db
Desktop.ini
.vscode/
.idea/
*.swp
*.swo
*~

# 6. Build, Dependency & Runtime Directories
node_modules/
__pycache__/
*.py[cod]
.venv/
venv/
dist/
build/
.next/
.cache/