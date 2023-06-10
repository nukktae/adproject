from flask import Flask, render_template, request

app = Flask(__name__)

@app.route('/action_page.php', methods=['POST'])
def handle_form_submission():
    student_id = request.form.get('email')
    password = request.form.get('psw')
    remember = request.form.get('remember')

    # Perform any necessary processing with the form data here
    # For example, you can store the data in a database or perform other operations

    # Placeholder response for demonstration purposes
    return "Form submitted successfully! Student ID: {}, Password: {}, Remember: {}".format(student_id, password, remember)

if __name__ == '__main__':
    app.run()
