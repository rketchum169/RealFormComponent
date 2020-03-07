## Contact Form Component

<img src="./DOC_Images/Baseform.png" width="400">

### Step 1: Download & Place in Your Components folder

Download the repo. After you have downloaded the folder. Add the ContactForm folder into your components project folder.

### Step 2: Import

The next step is to import the ContactForm component within your project. At the top of your specified file please copy and paste.

`import ContactForm from "./ContactForm/ContactForm.js"`

Wherever you would like to use the component, please call on the component using

`<ContactForm />`

You are now using the component. Congratulations.

### Step 3: Form field Customization

The greate thing about this component is it's Atomic Design. Everyone usually asks for something different so we built this component just for that. Within `ContactForm` folder, we have several
other components we'd like to refer to as "Atoms". Each with it's own unique properties to give you that level of customization you're dying to have. These other component files are as follows:

`Header.js`

`Label.js`

`TextArea.js`

`TextInput.js`

The components in the current form labeled:

<img src="./DOC_Images/LabelBaseform.png" width="400">

# Header Component & Prop

`<Header name="Contact Me" instruction="This is where you would write some informational text that would your user with their experience." >`
