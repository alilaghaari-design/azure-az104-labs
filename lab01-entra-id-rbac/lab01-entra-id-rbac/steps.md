# Step-by-Step Configuration

1. Created resource groups:
   - rg-it
   - rg-finance

2. Created Entra ID users:
   - it.admin@tenant.onmicrosoft.com
   - finance.user@tenant.onmicrosoft.com

3. Assigned RBAC roles:
   - IT Admin → Contributor
   - Finance → Reader

4. Created Azure Policy:
   - Required resource tagging
   - Denied public IP creation

