# ORV-Reader-Scenario-Window-Workskin-AO3
CSS for a workskin in AO3, modelling the formatting found in orv.pages.dev.

Features three blockquote classes for different types of text.

For system notifications, use "notice".
For bracketed text, use "bracket".
For Scenario Windows, use "window".

To use this workskin, you must create a private workskin in your profile. 
1. Go to Profile->Skins->My Workskins
2. Click "Create Work Skin"
3. Copy the CSS into the text box at the bottom
4. Title & Save the workskin.
5. When posting a draft/fic, under the associations tab, find "Select Work Skin" and choose the one you named.

Note that only one workskin can be present on a fic at a time.

Classes can be defined in a blockquote by typing `<blockquote class="[class name here]">[text here]</blockquote>`
A title can be added to the window class by adding a line for it: `<span class="title">[Main Scenario #1 – Proof of Value]</span>`

An example of the "window" class with a title included:
```
<blockquote class="window">
<span class="title"><p>[Main Scenario #1 – Proof of Value]</p></span>
<p>Category: Main</p>
<p>Difficulty: F</p>
<p>Clear Conditions: Kill one or more living things.</p>
<p>Time Limit: 30 minutes</p>
<p>Compensation: 300 coins</p>
<p>Failure: Death</p></blockquote>
```
