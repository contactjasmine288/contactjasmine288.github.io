# How to Edit the Website on GitHub (No Coding Required)

This guide walks you through making two common changes to the Redditch Smile Care website directly on GitHub — no technical knowledge needed.

---

## Before You Start

You will need:
- A **GitHub account** (free — sign up at github.com if you don't have one)
- To be added as a **collaborator** on the repository (ask your developer to add you)

---

## How to Open and Edit a File on GitHub

These steps are the same for every change below.

1. Go to: **github.com/contactjasmine288/contactjasmine288.github.io**
2. You will see a list of files. Click the file you want to edit.
3. Once the file opens, click the **pencil icon** (Edit this file) near the top-right of the file content.
4. The file will open in an editor. Use **Ctrl + F** (Windows) or **Cmd + F** (Mac) to search for the text you want to change.
5. Make your changes.
6. When done, scroll to the bottom of the page. Under **"Commit changes"**, type a short note (e.g. "updated phone number") and click the green **"Commit changes"** button.

The website will update automatically within a minute or two.

---

## Change 1: Phone Number

The phone number `01527 63049` appears across **multiple files**. You need to update it in each file separately.

### Files to update (one by one):

| File name | What it controls |
|---|---|
| `index.html` | Home page |
| `contact.html` | Contact page |
| `-dentist-private-fees.html` | Private fees page |
| `-dentist-nhs-fees.html` | NHS fees page |
| `nav.html` | Navigation bar |
| `team.html` | Our Team page |
| `review.html` | Reviews page |
| `complaint.html` | Complaints page |
| `privacy.html` | Privacy page |
| `cookies.html` | Cookies page |
| `emergency-dentist-.html` | Treatments page |

### Steps for each file:

1. Open the file (follow the "How to Open and Edit" steps above).
2. Press **Ctrl + F** to open the browser's Find tool.
3. Type `01527 63049` and press Enter.
4. Click on each highlighted match and change it to the new number.

   > **Important:** The number appears in two forms in the code. Replace **both** versions:
   > - `tel:01527 63049` — this is the hidden link (change just the number part)
   > - `01527 63049` — this is the visible number shown on the page

5. After replacing all occurrences in that file, scroll to the bottom and **Commit changes**.
6. Repeat for the next file in the list.

---

## Change 2: Private Treatment Prices

All private prices are in one file: **`-dentist-private-fees.html`**

### Steps:

1. Open the file `-dentist-private-fees.html` (follow the "How to Open and Edit" steps above).
2. Press **Ctrl + F** to find the treatment you want to update (e.g. type `Invisalign` or `Crown`).
3. Look for the price next to it. It will look like this in the code:

   ```
   <td data-label="Cost">From £650</td>
   ```

4. Change only the price amount (e.g. `£650` → `£700`). Do not change any surrounding text like `<td data-label="Cost">` or `</td>`.
5. Scroll to the bottom and **Commit changes**.

### Price sections available to edit:

| Section | Treatments included |
|---|---|
| Exam and Diagnostics | Initial, Routine, Emergency, X-rays, etc. |
| Orthodontics | Invisalign single/dual arch, Retainers, etc. |
| Hygienist | Routine Scaling |
| Amalgam Fillings | 1, 2, 3 Surface fillings |
| White Fillings | 1, 2, 3 Surface fillings |
| Extractions | Incisor, Pre Molar and Molar |
| Bridges | Fixed (per unit), Adhesive |
| Onlay | Onlay (depending on material) |
| Crown | All Ceramic |

---

## Change 3: NHS Treatment Prices

All NHS prices are in one file: **`-dentist-nhs-fees.html`**

### Steps:

1. Open the file `-dentist-nhs-fees.html` (follow the "How to Open and Edit" steps above).
2. Press **Ctrl + F** to find the treatment or band you want to update.
3. Change only the price text. Do not change anything else.
4. Scroll to the bottom and **Commit changes**.

---

## Tips to Avoid Mistakes

- **Only change the text between `>` and `<`** — for example, in `>From £75<`, only change `From £75`.
- **Do not delete** angle brackets `< >`, quote marks `" "`, or any words like `href`, `class`, `td`.
- If something looks wrong after saving, you can go to the file's **History** tab on GitHub and click **Revert** to undo your last change.
- If you are unsure, take a screenshot of the section before editing so you have a reference.

---

## Checking Your Changes

After committing, wait 1–2 minutes and then visit the live website to confirm the changes appear correctly:

- Home page: redditchsmilecare.co.uk
- Private fees: redditchsmilecare.co.uk/-dentist-private-fees.html
- NHS fees: redditchsmilecare.co.uk/-dentist-nhs-fees.html
- Contact: redditchsmilecare.co.uk/contact.html
