# TODO for Built-in Database Editor

This document outlines the tasks required to implement a built-in database editor within the Event Horizon main game(not EHF).

## Current Progress

- Initial task list created.
- ~~Learn how to use Unity.~~

## Tasks

1.  **Create a new Unity scene (`DBEditorScene`):** This scene will host the UI and logic for the built-in database editor.
    *   Location: `Assets/Scenes/DBEditorScene.unity` (don't have idea for another place)
2.  **Design and Implement UI:** Develop a user interface for viewing, editing, and saving database entries.
3.  **Implement Existing Database Editor Logic(C# Scripts):**
    *   **Loading:** YEAH
    *   **Editing:** ~~YEAH~~ Provide methods to modify data in memory.
        *   Ensure data integrity and validation during editing.
    *   **Saving:** ~~YEAH~~ Implement functionality to save modified data back to database files.
        *   Ensure the output format is consistent with the game's expectations for files.
    *   **Compile database:** YEAH
        * Export compiled Database into somewhere on mobile platform.
    *   **Multi-Platform:** YEAH
        * The ultimate goal of this project.
4.  **Update `README.md`:** ~~Document the new built-in database editor(hmm?).~~ YEAH
5.  **Testing:**
    *   IDK how to testing, if it work, it WORK!!!(if not it's bug).

This list will be updated as progress is made and new insights are gained.