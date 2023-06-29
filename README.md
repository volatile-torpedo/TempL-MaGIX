- [ ] 🚧 Move all instructions here

# 🚧 TO DO

- [ ] Add blank _spacer_: style, autocorrect for {{gap}}
- [ ] Update autocorrects for all three to include the {{gap}}
- [ ] Remove Coretek logo from document
- [ ] Remove sensitivity from document


## Decision, Limitation and Note blocks

- [ ] Remove bold from the opening words
- [ ] Double check the Language and spell check on those styles.
- [ ] Remove "automatically update" from the style definition
- [ ] 


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

What should you do instead? Simple, if you want to maintain the integrity (style, font, contents) of the document by making it read-only, then export it as a PDF! Additionaly, digitally sign the PDF and set it to block annotations
