
<!DOCTYPE html>
<html>
<head>
    <title>Job Application</title>
</head>
<body>
    <h1>Job Application Form</h1>
    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" required><br><br>

        <label for="phone">Phone:</label>
        <input type="tel" id="phone" required><br><br>

        <label for="dob">DOB:</label>
        <input type="date" id="dob"><br><br>

        <label for="url">Portfolio:</label>
        <input type="url" id="url"><br><br>

        <p>Preferred Shift:</p>
        <label><input type="radio" name="shift" value="day"> Day</label>
        <label><input type="radio" name="shift" value="night"> Night</label>

        <p>Skills:</p>
        <label><input type="checkbox" name="skills" value="html"> HTML</label>
        <label><input type="checkbox" name="skills" value="java"> Java</label>

        <br><br>
        <label for="qualification">Qualification:</label>
        <select id="qualification" required>
            <option value="">Select</option>
            <option>B.Tech</option>
            <option>BCA</option>
        </select><br><br>

        <label for="letter">Cover Letter:</label>
        <textarea id="letter"></textarea><br><br>

        <label for="status">Application Status:</label>
        <input id="status" value="Pending" disabled><br><br>

        <button type="submit">Apply</button>
    </form>
</body>
</html>
