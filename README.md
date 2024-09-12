# login.css
CSS (in style.css file):


body {
	background-color: #f0f0f0;
	font-family: Arial, sans-serif;
}

.login-container {
	width: 300px;
	margin: 50px auto;
	padding: 20px;
	background-color: #fff;
	border: 1px solid #ddd;
	border-radius: 10px;
	box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.login-form {
	display: flex;
	flex-direction: column;
}

.input-group {
	margin-bottom: 20px;
}

.input-group label {
	display: block;
	margin-bottom: 10px;
}

.input-group input {
	width: 100%;
	height: 40px;
	padding: 10px;
	border: 1px solid #ccc;
	border-radius: 5px;
}

button[type="submit"] {
	width: 100%;
	height: 40px;
	padding: 10px;
	background-color: #4CAF50;
	color: #fff;
	border: none;
	border-radius: 5px;
	cursor: pointer;
}

button[type="submit"]:hover {
	background-color: #3e8e41;
}
