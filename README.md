# Voice-based-note-taker

 ## Overview
  The **Voice Based Note Taker** is the web application that allows the user to create, edit, view, delete, save the notes using voice commands.
  The application uses **speech-to-text** technology to convert spoken words into written text, allowing user to dictate their notes hands-free.

  ## Objective
  - **Voice enabled note taking application**.
  - To create a simple user friendly design that works across devies like **desktop** , **mobile**.

  ## Project Workflow
  1. Home Page :
      1. **Purpose** : The main page where the user can record note using voice input and view previously created notes.
      1. **Features** :
          - Voice input button.
          - Displays the transcribed text of the text.
  2. Add Note Page :
      1. **Purpose** : Allows user to create new notes by dictating their speech, which is transcribed into text.
      2. **Features** :
            - **Voice input button** to start recording.
            - **Text** area to display the transcribed note.
            - **Save** button to save the notes the database.
  3. Notes List Page :
      1. **Purpose** : Displays all saved nots in the list format.
      2. **Features** :
            - List of saved notes with titles or snippets of text.
            - **Edit** and **Delete** options next to each note.
            - **Note** button to view the full content.
  4. Edit Note Page :
       1. **Purpose** : Enables users to modify an existing note.
       2.  **Features** :
            - Pre-filled text area with the existing note's content.
            - **Save** button to save the changes and **Cancel** button for the edit.
  5. Download Page :
        1. **Purpose** : Enables the user to download the notes in **.pdf** format.
  ## Tech Stack
  1. Frontend :
      - HTML
      - CSS
      - JavaScript
      - Web Speech API
  2. Backend :
     - Flask
     - MongoDb
  

     
