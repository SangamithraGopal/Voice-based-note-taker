# Pages

1. **Home Page**

- The Home Page serves as the main landing page of the application. It provides the user with the option to record a note via voice input and view previously created notes.

  1. *Features:*
     1. *Sign In / Sign Up Buttons* : Users need to log in or register before accessing the note-taking features.

     1. *Voice Input Button:* A button that triggers the voice recording feature, enabling the user to dictate their note.

      1. *Transcribed Text:* After the voice input is processed using **speech-to-text technology**, the transcribed text is displayed on the page, allowing the user to view the dictated note in real-time.

      1. *Links to Other Pages:* The user can easily navigate to other pages such as **"Add Note," "Notes List," and "Download Page."**

      1. *Navigation:* 
      - When the user successfully records a note, they can either save it directly or go to the **"Notes List Page"** to view saved notes.
      
2. **Add Note Page**

- The Add Note Page allows the user to create new notes by dictating their speech, which is transcribed into text.

  1. *Features:*

     1. *Voice Input Button:* A button that starts the voice recording to capture the note. This input will be transcribed into text and displayed on the page.

     1. *Text Area:* A text area where the transcribed note will appear. The user can review the content before saving it.

     1. *Save Button:* A button to save the transcribed note to the database (MongoDB).

     1. *Cancel Button:* A button to cancel the note creation and return to the previous page.

     1. *Navigation:*
     - Once the user clicks the "Save" button, the note is stored in the database, and they are redirected to the "Notes List Page."    
     - Clicking "Cancel" takes the user back to the "Home Page."

3. **Notes List Page**

- The Notes List Page displays all the notes saved by the user in a list format.

  1. *Features:*

       1. *List of Saved Notes:* Each saved note is displayed as a list item with a snippet of the note’s content or title.

       1. *Edit Option:* A button next to each note that allows the user to modify an existing note. Clicking this button will take the user to the "Edit Note Page."

        1. *Delete Option:* A button next to each note for deleting the note from the database.

        1. *View Option:* A button next to each note that lets the user view the full content of the note.

        1. *Navigation:* 
        - Clicking the "Edit" button redirects to the "Edit Note Page" where the user can modify the note.    
        - Clicking the "Delete" button removes the note from the database, and the user is redirected back to the "Notes List Page."
        - Clicking "View" will show the full note's content.
        
4. **Edit Note Page**

- The Edit Note Page allows the user to modify an existing note. This page pre-fills the text area with the existing note content for easy editing.

  1. *Features:*
   
     1. *Pre-filled Text Area:* The text area will be populated with the current content of the selected note, allowing the user to make changes.

     1. *Save Button:* A button to save the changes made to the note. Once saved, the note is updated in the database.

     1. *Cancel Button:* A button to cancel the editing process and return to the "Notes List Page" without making any changes.

     1. *Navigation:*
      - Clicking the "Save" button updates the note in the database, and the user is redirected back to the "Notes List Page."
      - Clicking "Cancel" takes the user back to the "Notes List Page" without saving changes.
      
5. **Download Page**

- The Download Page enables users to download all their saved notes in a PDF format. This page compiles all notes and generates a downloadable PDF file.

  1. *Features:*

       1. *Download Button:* A button that generates and allows the user to download the notes in PDF format. The PDF will contain the list of all notes and their content.

       1. *Note Listing in PDF:* The notes are listed in a clear format within the generated PDF file, preserving the original content of each note.
       
       1. *Navigation:* 
       - After downloading the PDF, the user can either return to the "Home Page" or continue navigating the app.
