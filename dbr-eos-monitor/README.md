# Databricks Runtime EOS Monitor - Asset Bundle
Monitor and alert on DBR at or nearing end of service.

This bundle creates:
- A notebook-based refresh job (`DBR_Lookup_Table.ipynb`)
- A dashboard (`DBR Days Until End Of Service Dashboard.lvdash.json`) that will be created in your workspace on deploy

## How to Use

## Quickstart (Workspace UI)
1. In your Databricks workspace, go to **Repos → Add Repo** and paste this Git URL.
2. Open the repo and click the **DABS** badge in the top bar.
3. Select target **dev** and click **Deploy**.
4. After deploy, open the created Dashboard (DBR Days Until End Of Support Dashboard) and the Job (DBR Monitor Refresh).

## Quickstart (CLI)
```bash
# Use your workspace profile
databricks bundle validate -t dev
databricks bundle deploy -t dev

