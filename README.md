[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22240065)
# An Introduction to Computer Software Development (Level 2 to Level 3 Bridging Course)

## Exercise: The Screenshot Challenge (HTML Structure)

In this exercise, you will be given a screenshot of a webpage. Your goal is to recreate the **structure** of that page as closely as possible using the HTML tags we have covered today.

**Note:** If you cannot see the image below, please open the file **"sample_page.png"** inside the "img" folder to view the challenge.

![Sample Page to be recreated](/img/sample_page.png)

**Remember:** Focus on the hierarchy (which headings are bigger?) and the type of lists used (ordered vs unordered). 

### Key Tags to Remember
- `<h1>` to `<h2>` – Content Hierarchy
- `<p>` – Standard Text
- `<ul>` and `<ol>` – Bulleted and Numbered Lists
- `<hr>` – Thematic Breaks (Horizontal Rules)
- `<a>` – Hyperlinks

---

## Task 1: Document Setup

Before you start coding the content, you must set up your file correctly.

### TODO
1. Create a new file in your workspace named `index.html`.
2. Add the basic HTML5 structure (the boilerplate).
3. Set the `<title>` of the page to "Project Showcase".
4. Ensure your `<html>` tag specifies `lang="en-GB"`.

---

## Task 2: Replicating the Content

Look at the provided screenshot. You need to identify which tags are needed to make the text appear in the correct format.

### TODO
1. Use an `<h1>` for the main page title.
2. Use a `<p>` for the introductory description.
3. Use an `<hr>` to create the horizontal line divider.
4. Use `<h2>` tags for the "Core Features" and "Installation Steps" sections.

---

## Task 3: Lists and Nesting

The screenshot contains two different types of lists. You must choose the correct one for each section.

### TODO
1. Recreate the **Core Features** section using an Unordered List (`<ul>`).
2. Recreate the **Installation Steps** section using an Ordered List (`<ol>`).
3. Ensure every item in your list is wrapped in `<li>` tags.

---

## Task 4: Adding the Visuals

The page includes a preview image. 

### TODO
1. Use the `<img>` tag to add an image. 
2. You can use any placeholder image or a screenshot of your previous Python program.
3. **Important:** Include a descriptive `alt` attribute for accessibility.

---

## Saving Your Work

Once your page structure matches the screenshot, save your work to your repository.

Run the following commands in the terminal:

1. `git add index.html`
2. `git commit -m "Completed screenshot challenge"`
3. `git push origin main`

---

## Extension Activities

### Extension 1: Hyperlinks

Make the "Developer Links" section functional.

#### TODO
1. Create a link that points to `https://github.com`.
2. Create a "mailto" link using your own email address.
3. Ensure the links have descriptive text so the user knows where they lead.

---

### Extension 2: Character Entities

Sometimes we need to display special characters that are reserved in HTML.

#### TODO
1. At the bottom of the page, add a footer.
2. Use the HTML entity `&copy;` to display the copyright symbol followed by "2026".

---

## Final Submission

Once you have finished your extensions, run the following commands in your terminal:

1. `git add index.html`
2. `git commit -m "Added extensions to challenge"`
3. `git push origin main`

---

