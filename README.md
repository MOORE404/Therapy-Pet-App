# Dog-Sitting App Prototype

A high-fidelity Figma prototype for a dog-sitting mobile app.

## Overview

This prototype focuses on intuitive interaction design, accessibility, and user-centered layout. Core features include Browse sitters, filtering by preferences, and viewing sitter profiles; all designed to support seamless, trustworthy booking experiences for pet owners.

View Figma Prototype: https://www.figma.com/proto/gt6NCbJmt4BonKkWXCAyvX/Prototype-%7C-HCI?node-id=0-1&t=WBGYZ1V64uM7ipXF-1

## Screenshots

<div align="center">

<table>
    <td align="center" colspan="3"><b>Pet Profile</b></td>
  </tr>
  <tr>
    <td><img src="Pictures/Max.png" width="260" height="460" style="object-fit: contain;"/></td>
    <td><img src="Pictures/MaxReviews.png" width="260" height="460" style="object-fit: contain;"/></td>
    <td><img src="Pictures/MaxAvailability.png" width="260" height="460" style="object-fit: contain;"/></td>
  </tr>
  <tr>
    <td align="center" colspan="3"><b>Filter Flow</b></td>
  </tr>
  <tr>
    <td><img src="Pictures/Filter.png" width="260" height="460" style="object-fit: contain;"/></td>
    <td><img src="Pictures/SelectAnimals.png" width="260" height="460" style="object-fit: contain;"/></td>
    <td><img src="Pictures/SelectDate.png" width="260" height="460" style="object-fit: contain;"/></td>
  </tr>
    <td align="center" colspan="3"><b>Navigation</b></td>
    <tr>
    <td><img src="Pictures/Browse.png" width="260" height="460" style="object-fit: contain;"/></td>
    <td><img src="Pictures/Enquiries.png" width="260" height="460" style="object-fit: contain;"/></td>
    <td><img src="Pictures/Settings.png" width="260" height="460" style="object-fit: contain;"/></td>
  </tr>
</table>

</div>

<div align="center">

<table>
  <tr>
    <td align="center" colspan="3"><b>Homepage – Apple Vision-style Preview</b></td>
  </tr>
  <tr>
    <td align="center" colspan="3">
      <img src="Appleversion.gif" width="260" height="460" style="object-fit: contain; border-radius: 10px;" alt="Homepage Vision Style Preview"/>
    </td>
  </tr>
  <tr>
    <td align="center" colspan="3">
      <i>I envisioned what this app may look like with apples upcoming glass UI and the future of ux innovation. My vision is a little excessive with the glass feature which will likely impact performance, but this is a vision for beyond the limitations of older iphones.</i>
    </td>
  </tr>
</table>

</div>




## Design Process & Choices

### Conceptual Module

After carefully considering the app's essential features, I organized its functionality into three main sections:
* **Homepage:** Designed to help users find and browse animals they wish to hire.
* **Enquiries Page:** Used to manage and access information about animals the user is looking to rent.
* **Settings Page:** Dedicated to tasks such as editing user accounts and managing login/logout functions.

### Target Audience & Core Principles

The app's target audience includes individuals experiencing anxiety or stress, those seeking emotional support, and healthcare professionals. To cater to this demographic, my prototype development prioritized user-friendliness, simplicity, and a clutter-free interface. My research identified key design principles: empowering users with control, making mindful color choices, employing simple design patterns, and ensuring a clear visual hierarchy.

### Color Palette & Accessibility

* **Color Choices:** A light blue color palette was chosen to evoke feelings of calmness, peace, loyalty, and trust, aligning with the therapeutic goal of the app for users with anxiety or depression. Green elements were integrated to introduce positivity and growth, supporting the potential goals of the users.
* **Muted Tones:** Dominant colors are muted to promote relaxation and prevent overwhelming users, especially those with anxiety.
* **Contrast & Colorblindness:** I utilized contrast and colorblind checkers for every page to ensure no poor color choices were overlooked, especially for text readability. This step was crucial as initial designs had some hard-to-read text instances.

### Page-Specific Design Breakdown

#### Homepage (Browse)

This page focuses on **cognitive building blocks** and **Fitts' Law**:
* **Proximity:** Information for each dog is grouped closely with its picture, making it clear which details belong to which animal.
* **Similarity:** Dog profiles maintain a consistent format (picture on the left, followed by information), helping users quickly understand the structure and scan for desired information.
* **Metaphors:** Icons representing dog 'stats' act as metaphors, visually chunking information for quicker scanning and comparison.
* **Visual Borders:** Profiles are separated by white space, creating clear visual boundaries to differentiate animals and prevent clutter.
* **Fitts' Law Application:** Dog profiles are sufficiently large to be easily tappable, adhering to the recommended minimum touch target size of 48x48 density-independent pixels with 8 pixels or more of spacing, ensuring usability.
* **Optimal Layout for Thumb Interaction:** Frequently used controls, such as viewing animal profiles and the navigation bar, are positioned for easy access, typically closer to the user's thumb starting point to reduce movement.
* **Filter Placement:** Filters are placed at the top of the screen because they are used less frequently, are highly visible and prominent, and align with common design patterns found in popular apps like Amazon and Google Maps, promoting consistency.
* **Natural Gestures:** The design incorporates natural swipe gestures for certain actions, enhancing intuitiveness and efficiency.
* **Manageable Targets:** Approximately four dog profiles are visible at a time, providing a manageable number of targets for users to interact with, aligning with the 7 +/- 2 guideline.

#### Animal Profile Page

This page prioritizes **user control**, **information hierarchy**, and **recognition over recall**:
* **Information Hierarchy:** The page is carefully structured, starting with basic animal stats and pictures, then breaking down more detailed information into three distinct sections: 'Info', 'Reviews', and 'Availability'. This approach prevents overwhelming the user and allows them to control the order in which they explore information, offering a comprehensive understanding.
* **Shneiderman's Golden Rules:**
    * **Consistency:** A consistent layout is maintained across the 'Info', 'Reviews', and 'Availability' sections, aiding users in building a mental model for navigation.
    * **User Control:** Users can freely browse the animal's profile and choose which sections to explore, providing a sense of control over their interaction.
    * **Reduced Memory Load:** Information is presented clearly and concisely with limited text and metaphors, reducing the need for users to hold excessive information in short-term memory.
    * **Easy Reversal of Actions:** Users can easily return to the homepage by clicking the top-left arrow or the homepage icon in the navigation bar, a common and recognizable design pattern.
* **Control Types:** Buttons for 'Info', 'Reviews', and 'Create Inquiry' have clear text labels indicating their function, reducing ambiguity.
* **Fitts' Law (Buttons):** 'Info', 'Reviews', and 'Create Inquiry' buttons are large enough to be easily tappable, improving selection time. While spacing between 'Info' and 'Reviews' is minimal, Gestalt principles of grouping were intended to clarify their interactive nature.
* **Prioritized Buttons:** The section buttons and 'Create Inquiry' button are positioned for easy access due to their importance.
* **Recognition over Recall:** The page is designed to encourage scanning by simplifying animal statistics into metaphors and short sentences.

#### Enquiries Page

This page emphasizes **scannability**, **visual hierarchy**, and **affordances**:
* **Easy Scannability:** A list format with clear headings allows users to quickly scan and locate specific inquiries. Capital letters for the selected inquiry further enhance scannability.
* **Clear Visual Hierarchy:** White space separates inquiries to avoid clutter, and bold text for inquiry titles combined with subtler text for details creates a visual hierarchy that guides user attention.
* **User Control & Feedback:** 'Pay' and 'Cancel Booking' buttons provide clear affordances, visually indicating they are clickable elements for action. The price displayed next to the 'pay' button offers immediate feedback before payment commitment.
* **Learnability:** The combination of icons and text (e.g., message icon for sending a message) enhances learnability, even for first-time users.
* **Clustered Controls:** Frequently used buttons are grouped closely together within a comfortable reach for the user.

#### Settings Page

The settings page focuses on **ease of use** and **prioritization**:
* **Familiar Structure:** Settings are structured similarly to popular apps like WhatsApp, using categories such as 'Account', 'Notifications', 'Appearance', 'Help and Support', 'About', and 'Logout' for a smooth navigation experience.
* **Search Functionality:** A search function is included to enhance ease of use, allowing users to quickly find specific settings (e.g., a specific notification) without having to browse through multiple categories.
* **Category Prioritization:** Categories are prioritized, with the most frequently accessed ones (like 'Account settings') positioned at the top for enhanced accessibility. Less frequent but crucial actions like 'Logout' or 'Delete' are intentionally placed lower to avoid reducing the visibility of more important features.

## Overall Prototype Approach

My prototype adopts a more **vertical** than horizontal design, providing high detail and deeply exploring the app's functionality. All images and icons used were sourced from the same website, and Figma templates were utilized to aid in the design progression. Inspiration for the color scheme was drawn from external websites, which have been cited.

## Tools Used

-   **Figma** – UI/UX Design, High-Fidelity Prototyping
-   **UX Research** – User personas, usability testing, and design iteration
-   **Accessibility Design** – High contrast, clear navigation, and inclusive interaction patterns

## Notes

-   Created for the University of Nottingham’s Human-Computer Interaction module — graded 79%.
-   Designed using Gestalt principles, colour psychology, and feedback from usability tests.
