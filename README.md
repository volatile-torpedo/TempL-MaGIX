**Template Library - Markup and Generation of Improved Documentation**
📃Microsoft Word template that includes styles and several elements to create professional technical documents. 💡Equally useful, the instructions include a variety of tips to create and manage document templates. 


# 🚧 TO DO

- [ ] Add blank _spacer_: style, autocorrect for {{gap}}
- [ ] Update autocorrects for all three to include the {{gap}}
- [ ] Remove Coretek logo from document
- [ ] Remove sensitivity from document
- [ ] Update "Next Steps":
  - Rename Timeline to Timeframe
  - Rename Urgency to Impact or Risk
  - Rename Importance to Priority
  - Remove "VCW"


## Decision, Limitation and Note blocks

- [ ] Remove bold from the opening words
- [ ] Double check the Language and spell check on those styles.
- [ ] Remove "automatically update" from the style definition
- [ ] Create custom bullets from graphics to open the custom blocks


## ℹ️ Tips
- [ ] How to change the date format for the Published Date field. Select field > Developer > Controls > Properties.
  - Reference: https://office-watch.com/2018/publish-date-mapped-content-controls-word/
- [ ] Watermarks
- [ ] Upload the template to a SharePoint site

## 🔎 Explain (maybe)
- [ ] How Word manages templates.
- [ ] What template elements "stick" after document is saved



# Post these elsewere
### What Happens When you Mark a Document as **Final**:
To prevent the team from modifying the documents, use the "Mark as Final" feature before sharing the documents. The Mark as Final command makes the documents read-only, i.e. typing and proofing marks are disabled. Furthermore, the Status property of the document is also changed to "Final". Once set, they can't change the final document by accident, and THAT'S THE ONLY REASON TO USE THIS FEATURE.
![image](https://github.com/volatile-torpedo/Word-StyleFrame/assets/106129332/9c563d52-cc28-48bb-97d1-47c355904e71)

Why? Because as long as the document is not in a protected folder, people can still remove the "Mark as Final" status and then edit it.
![image](https://github.com/volatile-torpedo/Word-StyleFrame/assets/106129332/577ff898-e2bb-4747-8b09-779dd97ccc17)

Result:

![image](https://github.com/volatile-torpedo/Word-StyleFrame/assets/106129332/ae6f2204-5e91-4acd-885c-8462b7fade69)

**What should you do instead?** Simple, if you want to maintain the integrity (style, font, contents) of the document by making it read-only, then export it as a PDF! Additionaly, digitally sign the PDF and set it to block annotations

### Documents stored in SharePoint and Teams are unreadable when opening with the desktop app
Yes, even this far along, documents can be corrupted when editted by multiple people concurrently. This is especially true with complex documents with multiple styles and using fonts that aren't built in to the application during the initial install.

When it happens, and everyone else is running into the same thing, then you can try to repair it, then copy and paste the contents nito a new document. Then overwrite the original with the new version while keeping a backup of it for when it happens again.

** What should I do instead?** Use the Check-Out and Check-In feature. This will prevent multiple people from opening it in edit mode. When you check out a file from a SharePoint document library, only you can edit it. You can edit the file offline and save your changesbefore checking the file back in. Once you're done making changes to the file, check it in from the library to uplooad your changes.You can also disregard them. 

> ℹ️ **Note** When you check out a file, nothing happens to it. The file is still stored in the library. It's just marked to show that you have exclusive editing rights until you check it back in. To edit it, you must download the document or edit it online. How you edit or update the file depends on the type of file. If it's a Word document, you can use Word in Microsoft 365 or your desktop copy of Word. For a file that isn't an Microsoft 365 format, download the file and use whatever editor you normally use for that format.
