 <style>
 h2{color:brown;text-align: center;}
 div{margin: 10px;}
 label{color:green;}
 input[type=text],input[type=password],input[type=number],select{width: 90%;padding: 10px;color:
blue; font-size: 18px;
 background-color: antiquewhite;border: 1px solid green;}
 input:focus{outline: none; background-color: azure;}
 .cssclr{color: red; }
 button{border: 1px solid green;color: green;padding: 5px;}
 .cssright{text-align: right;}
 button:hover{background-color: green;color: white;border: none;padding: 5px;}
 </style>
</head>
<body>
 <h2>Registration Form</h2>
 <form>
 <div>
 <label>Enter Name:</label>
 <input type="text" id="txtName" />
 </div>
 <div>
 <label>Enter regno:</label>
 <input type="text" id="txtpswd" />
 </div>
 <div>
 <label>Enter Mobile no:</label>
 <input type="number" id="txtName" />
 </div>
 <div>
 <label>Select City:</label>
 <select>
 <option>--Select--</option>
 <option>Mysuru</option>
 <option>Bangalore</option
 <option>Hassan</option>
 <option>Mandya</option>
 </select>
 </div>
 <div class="cssclr">
 <label >Select Course</label>
 <input type="radio" name="rbtn" />Computer Science
 <input type="radio" name="rbtn" />Mechanical
 <input type="radio" name="rbtn" />Civil
 <input type="radio" name="rbtn" />Electronics
 </div>
 <div class="cssright">
 <button>Register</button>
 </div>
 </form>
