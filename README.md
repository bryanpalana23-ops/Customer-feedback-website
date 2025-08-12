<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Velocity Motors Customer Feedback Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 30px;
      background: #f9f9f9;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .form-section {
      background: #fff;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input[type="text"], input[type="date"], textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .options {
      margin-top: 10px;
    }
    .options label {
      font-weight: normal;
      margin-right: 15px;
    }
    .grid-table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    .grid-table th, .grid-table td {
      border: 1px solid #ccc;
      padding: 8px;
      text-align: center;
    }
    .scale {
      display: flex;
      justify-content: space-between;
      margin-top: 10px;
    }
    .scale label {
      flex: 1;
      text-align: center;
    }
    button {
      margin-top: 20px;
      padding: 10px 20px;
      background: #d32f2f;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background: #b71c1c;
    }
  </style>
</head>
<body>

  <h2>Velocity Motors Customer Feedback Form</h2>

  <form>
    <div class="form-section">
      <label>Customer Name:</label>
      <input type="text" name="customerName">

      <label>Plate Number:</label>
      <input type="text" name="plateNumber">

      <label>Service Date:</label>
      <input type="date" name="serviceDate">

      <label>Branch:</label>
      <input type="text" name="branch">
    </div>

    <div class="form-section">
      <label>1. Booking Experience:</label>
      <div class="options">
        <label><input type="radio" name="booking" value="Very Easy"> Very Easy</label>
        <label><input type="radio" name="booking" value="Easy"> Easy</label>
        <label><input type="radio" name="booking" value="Neutral"> Neutral</label>
        <label><input type="radio" name="booking" value="Difficult"> Difficult</label>
        <label><input type="radio" name="booking" value="Very Difficult"> Very Difficult</label>
      </div>
    </div>

    <div class="form-section">
      <label>2. Service Day Experience:</label>
      <table class="grid-table">
        <tr>
          <th>Item</th>
          <th>Excellent</th>
          <th>Good</th>
          <th>Fair</th>
          <th>Poor</th>
        </tr>
        <tr>
          <td>Courtesy of Staff</td>
          <td><input type="radio" name="staff" value="Excellent"></td>
          <td><input type="radio" name="staff" value="Good"></td>
          <td><input type="radio" name="staff" value="Fair"></td>
          <td><input type="radio" name="staff" value="Poor"></td>
        </tr>
        <tr>
          <td>Waiting Time</td>
          <td><input type="radio" name="waiting" value="Excellent"></td>
          <td><input type="radio" name="waiting" value="Good"></td>
          <td><input type="radio" name="waiting" value="Fair"></td>
          <td><input type="radio" name="waiting" value="Poor"></td>
        </tr>
        <tr>
          <td>Accuracy of Service Time Estimate</td>
          <td><input type="radio" name="accuracy" value="Excellent"></td>
          <td><input type="radio" name="accuracy" value="Good"></td>
          <td><input type="radio" name="accuracy" value="Fair"></td>
          <td><input type="radio" name="accuracy" value="Poor"></td>
        </tr>
        <tr>
          <td>Quality of Work Performed</td>
          <td><input type="radio" name="quality" value="Excellent"></td>
          <td><input type="radio" name="quality" value="Good"></td>
          <td><input type="radio" name="quality" value="Fair"></td>
          <td><input type="radio" name="quality" value="Poor"></td>
        </tr>
        <tr>
          <td>Cleanliness of Vehicle After Service</td>
          <td><input type="radio" name="cleanliness" value="Excellent"></td>
          <td><input type="radio" name="cleanliness" value="Good"></td>
          <td><input type="radio" name="cleanliness" value="Fair"></td>
          <td><input type="radio" name="cleanliness" value="Poor"></td>
        </tr>
      </table>
    </div>

    <div class="form-section">
      <label>3. Communication:</label>
      <div class="options">
        <label><input type="radio" name="communication" value="Yes, frequently"> Yes, frequently</label>
        <label><input type="radio" name="communication" value="Yes, but not enough"> Yes, but not enough</label>
        <label><input type="radio" name="communication" value="No"> No</label>
      </div>
    </div>

    <div class="form-section">
      <label>4. Payment Experience:</label>
      <div class="options">
        <label><input type="radio" name="payment" value="Very Convenient"> Very Convenient</label>
        <label><input type="radio" name="payment" value="Convenient"> Convenient</label>
        <label><input type="radio" name="payment" value="Neutral"> Neutral</label>
        <label><input type="radio" name="payment" value="Inconvenient"> Inconvenient</label>
      </div>
    </div>

    <div class="form-section">
      <label>5. Overall Satisfaction:</label>
      <p>On a scale of 1–10, how likely are you to recommend Velocity Motors to a friend or family?</p>
      <div class="scale">
        <label><input type="radio" name="recommend" value="1"> 1</label>
        <label><input type="radio" name="recommend" value="2"> 2</label>
        <label><input type="radio" name="recommend" value="3"> 3</label>
        <label><input type="radio" name="recommend" value="4"> 4</label>
        <label><input type="radio" name="recommend" value="5"> 5</label>
        <label><input type="radio" name="recommend" value="6"> 6</label>
        <label><input type="radio" name="recommend" value="7"> 7</label>
        <label><input type="radio" name="recommend" value="8"> 8</label>
        <label><input type="radio" name="recommend" value="9"> 9</label>
        <label><input type="radio" name="recommend" value="10"> 10</label>
      </div>
    </div>

    <div class="form-section">
      <label>6. Suggestions for Improvement:</label>
      <textarea rows="4" name="suggestions"></textarea>
    </div>

    <button type="submit">Submit Feedback</button>
  </form>

</body>
</html>
