# Orderly Free Beta

**Windows · v1.0.0-beta.1**

**A local-first file organizer for Windows built around Preview → Run → Undo.**

Orderly turns cluttered folders into a plan you can review. See which files match your profile, where they will go, and which actions will run.

Create a profile, select the folders you want to organize, review the proposed file actions in **Preview**, and choose **Run** only when the plan looks right.

If you need to go back, completed runs are recorded in local **History** and can be reversed with **Undo** when possible.

---

## Preview → Run → Undo

Orderly is designed around a simple workflow:

1. Create a profile.
2. Select one or more folders.
3. Choose the file categories you want to organize.
4. Configure filters and organization options.
5. Preview the proposed file actions.
6. Review the plan.
7. Choose **Run** when you are ready.
8. Use **History → Undo** if you need to reverse a completed run.

Preview does not organize your files.

Nothing is automatically organized unless you explicitly enable **Auto-apply** for a profile you trust.

---

## Features

### Profiles

Create reusable profiles for folders such as:

- Downloads
- Desktop
- Media folders
- Camera imports
- Project folders
- Archive folders

Each profile stores its own folders, categories, filters, and organization settings.

### Five built-in categories

Orderly Free Beta supports:

- Images
- Videos
- Audio
- Documents
- Archives

### Preview

See the proposed organization before running it.

Review:

- files found
- categories
- destinations
- individual file actions
- files that will remain untouched

If something does not look right, adjust the profile and Preview again.

### Move or Copy

Profiles can organize files using either:

- **Move**
- **Copy**

### Collision handling

When a destination already contains a file with the same name, Orderly can:

- Keep both with a new name
- Skip the incoming file
- Overwrite the existing destination

For important folders, **Keep both** is generally the safest option.

### Filters

Profiles can be narrowed using filters for:

- included extensions
- excluded extensions
- excluded folders
- excluded file patterns
- file size
- file age/date
- subfolders

### Local History

Completed runs are recorded locally in **History**.

History keeps the sequence of the approved plan, completed organization, and completed restore when Undo is used.

### Undo

Orderly supports Undo for completed runs.

For **Move** runs, Undo moves the file currently at the recorded destination back to its original path when possible.

For **Copy** runs, Undo removes the file currently at the recorded destination while leaving the original source file in place.

Undo does not store snapshots of previous file contents.

If files are edited, replaced, moved, renamed, or deleted after a run, Undo may not be able to restore the original state.

Files replaced through the **Overwrite** collision option cannot be recovered by Undo.

**Undo is a safety net, not a replacement for backups.**

---

## Watch

Watch can monitor a profile for folder changes while Orderly is running. Closing the window keeps Orderly in the Windows system tray, so Watch can continue. Choose **Quit Orderly** from the tray to stop the app and its background watching.

**Watch alone does not organize files.**

It only detects changes.

Watch can be enabled per profile and does not have the one-profile Free Beta limitation applied to Auto-apply.

---

## Auto-apply

Auto-apply is optional and must be explicitly enabled.

When enabled, Orderly can organize newly detected files automatically according to the profile's existing rules.

Use Auto-apply only with a profile whose behavior you already trust.

**Orderly Free Beta allows Auto-apply on one profile.**

The normal manual workflow remains:

**Preview → Run → Undo**

---

## Local-first

Orderly is designed around local control.

Your selected folders are scanned and organized on your own computer.

Orderly does **not** upload the contents of the folders you organize to KenoLabs.

The following remain local:

- Profiles
- Settings
- Previews
- Run History
- Undo records
- Reports
- Diagnostic exports

No Orderly account is required for Free Beta.

---

## Privacy

Optional Free Beta feedback is sent only after you explicitly press **Send feedback**.

Feedback may contain limited technical information such as:

- feedback category
- your message
- app version
- operating-system platform
- edition
- environment
- locally generated installation identifier

The lightweight feedback request does not attach your:

- files
- file names
- folder paths
- profiles
- History
- logs
- reports
- diagnostic ZIP files

Orderly Free Beta does not silently upload diagnostic archives and does not include automatic feature-usage telemetry.

---

## Appearance

Orderly includes:

- Light
- Dark
- OLED Dark

Additional settings include:

- English interface
- completion notifications
- report export preferences
- hiding personal paths in reports
- startup update checks

---

## Updates

Orderly checks the official GitHub update manifest when you manually check for updates or enable startup update checks.

If a newer version is available, Orderly can show the available version and open the matching Windows installer download after you choose **Download installer**.

Orderly does **not** silently download or install updates.

---

## Free Beta

Orderly is currently available as **Free Beta**.

Free Beta includes:

- Profiles
- Five built-in categories
- Preview
- Run
- Move and Copy modes
- Filters
- Local History
- Undo
- Watch
- Auto-apply for one profile
- Appearance options
- English interface
- Completion notifications
- Reports
- Update checks


---

## Installation

Download the latest Windows installer from:

**[GitHub Releases](https://github.com/kenolabs11-sys/orderly/releases)**

After installation:

1. Open Orderly.
2. Create a profile.
3. Add a folder.
4. Select your categories.
5. Save the profile.
6. Choose **Scan files** or open Preview.
7. Review the proposed actions.
8. Choose **Run** only when the plan looks right.

---

## Important safety note

Orderly modifies real files when you choose Run or enable Auto-apply.

Keep independent backups of important files.

Undo can help reverse completed Orderly actions, but it cannot replace a normal backup or recover every possible later change to a file.

---

## Documentation

**Product page**  
[kenolabs.dev/orderly](https://kenolabs.dev/orderly)

**User guide**  
[Setup and workflow documentation](https://kenolabs.dev/orderly/docs)

**Changelog**  
[Version history](https://kenolabs.dev/orderly/changelog)

**Privacy Policy**  
[Orderly Privacy](https://kenolabs.dev/orderly/privacy)

**Terms of Use**  
[Orderly Terms](https://kenolabs.dev/orderly/terms)

---

## Feedback

Orderly is currently in Free Beta.

If you encounter a problem, describe:

- the type of folder you were organizing
- the relevant profile settings
- what you expected to happen
- what actually happened

Avoid sending private files or personal paths unless you intentionally want to share them.

---

<p align="center">
  <strong>Your folders, finally in order.</strong>
</p>

<p align="center">
  Preview → Run → Undo
</p>

<p align="center">
  © 2026 KenoLabs
</p>
