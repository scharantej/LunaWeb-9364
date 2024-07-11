### HTML Files

#### `index.html`
- This is the main HTML file that will serve as the front page of your website.
- It will contain the necessary HTML code to structure the website's layout, including headers, footers, and main content sections.
- Utilize Bootstrap classes to enhance the visual appeal and responsiveness of the website.

#### `about.html`
- This HTML file will provide information about the website or organization.
- Include relevant content such as the mission statement, team members, or contact details.
- Ensure clarity and conciseness in presenting the information.

#### `contact.html`
- This HTML file will allow users to contact the website or organization.
- Include a form with fields for user input, such as name, email, and message.
- Implement appropriate validation to ensure proper input before submitting the form.

### Routes

#### `@app.route('/')`
- This route is associated with the `index.html` file and will display the main page of the website.
- It should be defined as the root route of the application.

#### `@app.route('/about')`
- This route is associated with the `about.html` file and will display the about page of the website.
- It will provide information about the website or organization as defined in the HTML file.

#### `@app.route('/contact')`
- This route is associated with the `contact.html` file and will display the contact form.
- It will allow users to submit their queries or messages to the website or organization.