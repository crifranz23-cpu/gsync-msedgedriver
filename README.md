# gsync-msedgedriver

Auto-updated msedgedriver.exe for GSync - DataAgent.
Updated daily via GitHub Actions to match the latest Microsoft Edge stable version.

---

## How to Update msedgedriver on the Host PC

Do this whenever GSync warns about a driver version mismatch.

### Step 1 - Download the latest driver

Open the link below in Edge on the host PC, then save the file.

Direct download link:
https://github.com/crifranz23-cpu/gsync-msedgedriver/raw/main/msedgedriver.exe

### Step 2 - Replace the old driver

Copy the downloaded msedgedriver.exe into your app folder and replace the old one.

### Step 3 - Restart GSync

Close and reopen GSyncDataAgent.exe.
The Settings tab should now show Version match.

---

## How Often Is This Updated?

Every day at midnight UTC which is 8:00 AM Philippine Time.
The workflow checks the latest Edge version and commits a new driver if needed.

---

## Manual Trigger

If you need the driver updated immediately go to the Actions tab on this repo,
click Update msedgedriver, then click Run workflow.
