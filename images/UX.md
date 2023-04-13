# User Experience (UX)

## forms

- STRONG INFORMATION ARCHITECTURE: To build better forms, you first need to take a few steps away from your database’s structure. Try to understand how users want to fill in forms. Which steps do they expect? What come first? What comes next? This will give you a better idea of how to structure your form in a more user-friendly way.  

- LABEL PLACEMENT AND INPUT OPTIMIZATION:
  - Single-Column Layout Works Best.
  - labels on the left and inputs on the right.
  - Labels Should Be Clear And Visible And Work Without Context.
  - Size of the input element should match the size of the expected content.

- USING MASKS TO AVOID SPLITTING INPUTS ON MOBILE:
  - Don’t split inputs just for the sake of formatting.
  - Prevent errors by guiding users.
  - Avoid putting fake values in the mask.

- EFFICIENT FIELDS DESCRIPTIONS:
  - What Exactly Are You Asking For?
  - Why Do You Need This Information?
  - Where Do I Find the Information?
  - How Should I Format The Information?
  - How To Display Descriptions

- BE CAREFUL WITH PLACEHOLDERS:
  - Rely on short-term memory to remember what they are supposed to put in the field.
  - It’s hard for users to double-check fields before submitting because the fields no longer have any label indications.
  - It’s hard to recover from errors once a field has been submitted because, again, there’s no label to help the user.
  - It’s hard to tell the difference between a filled field and a field with a placeholder.
  - Placeholders are not mandatory in HTML5.
  - Labels inside fields could, nevertheless, work well for short forms in which fields are predictable.

- REDUCE THE NUMBER OF FIELDS  

- OPTIMIZING TOUCH INTERACTIONS:
  - Make your labels, fields and form controls easy to tap by increasing the touch target size.
  - Providing Feedback.
  - Honor The Next And Previous Button Order.

- AVOID DROPDOWNS ON MOBILE IF POSSIBLE:
  - Segment controls and radio buttons.
  - Long dropdowns can be replaced by predictive text input fields.
  - If you need users to pick a date, forget about splitting it into a day, month and year dropdown like people are used to doing on paper forms.
  - Replace multiple date dropdowns with a date picker.
  - The options would be listed in a specific subview, as radio buttons, for instance.  

- GETTING SMART WITH AUTO-COMPLETION:
  - Places and Addresses:
    - Google Places API
    - Algolia Places, which is based on OpenStreetMap.
  - Using HTML5 Autocompletion (Autofill).

- AVOIDING ERRORS WHILE FILLING THE FORMS:
  - Explicit Format Limitation.
  - Marking Mandatory Fields (And Optional Ones):
    - You could instead explicitly mark both mandatory and optional fields with the words “required” (or “mandatory”) and “optional”.
  - Be careful about default selected options in forms.
  - Smart defaults, on the other hand, can help users avoid mistakes when filling a form.
  - Less Painful Password Experience:
    - Tell users your password criteria up front.
    - A lot of websites now show you a gauge for password strength telling you in real time what is missing.
    - Provide a mask/unmask option.
  - Inline Validation:
    - Instead, error messages should be located close to the errors themselves.
  - Real-Time Validation:
    - You can validate fields and display feedback while the user is filling them in.

- COLOR MATTERS:
  - Non-colorblind users know that red is for errors, yellow is for warnings, and green is almost always for confirmation or success.
  - Speaking of colorblindness: Color should not be the only way to convey an error message.

- RECOVERING FROM ERRORS: WRITING USER-FRIENDLY ERROR MESSAGES:
  - You’re Not A Robot, And Neither Are Your Users. Yet so many error messages are still so poorly written:
    - Explain what happened in human language and why it happened.
    - Suggest ways to recover from the error.
    - Make error messages informative and consistent.
    - Explain to them in plain language, without technical jargon, how to recover from this error.
  - Beware The Language You Use In Messages:
    - Avoid making people feel stupid about a mistake.
    - If possible, leave out negative words.
    - Don’t blame users for mistakes; blame the system instead.
    - A little trick is to read your own message out loud.
    - You could also get creative with error messages and incorporate imagery and humour to make them less threatening.

- TIME TO SUBMIT THE FORM:
  - **The first rule is, don’t mask the submit button**. Seriously! I wonder what twisted mind came up with this idea, but I’ve seen it in some forms. The submit button would be displayed only once all required fields were filled in without any errors. It’s disturbing for the user to wonder whether something is wrong or the form’s button has not loaded or the website is broken and so on.
  - Use the disabled HTML attribute on the submit input. You will need to re-enable the button using JavaScript once the form is valid and ready for submission.
  - If you have a primary and secondary call to action, use color, size and styling to show the hierarchy.

- CALL TO ACTION:
  - Give the call to action descriptive, actionable verbs.
  - Provide visual feedback when the user taps it.
  - If you have two buttons, make the primary action stand out.
  - Unless you’re working on a very specific back-office enterprise form (in which case, you’ll have a lot of challenges optimizing for mobile), avoid a reset button. Users might confuse it with the submit button and will lose all of their data by accident.

- CONCLUSION:
  - Always test your forms on real users and real devices, and adapt the guidelines to your users’ specific needs and experience.
