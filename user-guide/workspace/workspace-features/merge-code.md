# Merge Code

Merges two source codes into one code.

This can be used in version control to resolve conflicts directly when they arise. Even without merging, you can easily see the differences between the two source codes.

Use it via the **\[Edit] > \[Merge]** submenu. Shortcuts are available to make the feature more convenient.

* **Merge View (`Alt + Shift + M (Mac: ⌥⇧M)`):** When launched, first select the two files you want to merge. Pressing the **`OK`** button will open an editor showing the differences between the two source codes.
* **Next Diff (`Alt + Shift + = (Mac: ⌥⇧=)`):** Moves to the next difference closest to the current cursor. The background colour changes when the difference is selected.
* **Previous Diff (`Alt + Shift + - (Mac: ⌥⇧-)`):** Moves to the previous difference closest to the current cursor. The background colour changes when the difference is selected.
* **Merge Diff (`Alt + Shift + / (Mac: ⌥⇧/)`):** Overwrites the currently selected differences from the right editor into the left editor. You can also merge by pressing the arrow icon (**`<~`**) in the centre of the merge editor. If no differences are selected, the first difference is merged.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-legacy-files%2Fo%2Fassets%252F-Lq-Q9LciN1X9EABxGkt%252F-LvySq9HN831gjmHVAfe%252F-LvyYsEkuzJa-GlciXC9%252Fimage.png%3Falt%3Dmedia%26token%3D0fc2ffab-c69d-4cd1-b20d-f31297a58f0f&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=2b4e4f17&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Press the **`=><=`** icon at the bottom centre of the merge editor to untie or untie the scrolls of both editors. T he default state is that the scrolls in both editors move together. If you untie the scrolls, the scrolls in both editors will move independently.

After merging, saving will save the merged content in the original left editor. The right editor is unmodifiable. The code merge window is not persisted across refreshes.
