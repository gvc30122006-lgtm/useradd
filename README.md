<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-commerce Users</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f5f5f5;
        }

        h1 {
            text-align: center;
            margin-bottom: 20px;
        }

        .user-table-container {
            max-width: 900px;
            margin: auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .top-buttons {
            display: flex;
            justify-content: flex-end;
            margin-bottom: 15px;
            gap: 10px;
        }

        .top-buttons button {
            padding: 10px 20px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 14px;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .add-btn {
            background-color: #28a745;
            color: white;
        }

        .add-btn:hover {
            background-color: #218838;
        }

        .edit-btn {
            background-color: #007bff;
            color: white;
        }

        .edit-btn:hover {
            background-color: #0056b3;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        th {
            background-color: #007bff;
            color: white;
        }

        tr:hover {
            background-color: #f1f1f1;
        }

        .action-btn {
            padding: 5px 10px;
            border: none;
            border-radius: 5px;
            color: white;
            cursor: pointer;
            font-size: 12px;
        }

        .edit-action {
            background-color: #ffc107;
        }

        .edit-action:hover {
            background-color: #e0a800;
        }

        .delete-action {
            background-color: #dc3545;
        }

        .delete-action:hover {
            background-color: #c82333;
        }
    </style>
</head>
<body>
    <h1>E-commerce Users</h1>

    <div class="user-table-container">
        <div class="top-buttons">
            <button class="add-btn">Add User</button>
        </div>

        <table>
            <thead>
                <tr>
                    <th>ID</th>
                    <th>Name</th>
                    <th>Email</th>
                    <th>Role</th>
                    <th>Action</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1</td>
                    <td>Likhitha</td>
                    <td> likhitha@gmail.com</td>
                    <td>Admin</td>
                   
                    <td>
                        <button class="action-btn edit-action">Edit</button>
                        
                    </td>
                </tr>
                 <tr>
                    <td>2</td>
                    <td>Anisa</td>
                    <td> anisa@gmail.com</td>
                    <td>User</td>
                   
                    <td>
                        <button class="action-btn edit-action">Edit</button>
                        
                    </td>
                </tr>
                
                <tr>
                    <td>3</td>
                    <td>Yasaswini</td>
                    <td>yashu@gmail.com</td>
                    <td>User</td>
                    
                    <td>
                        <button class="action-btn edit-action">Edit</button>
                        
                    </td>
                </tr>
              <tr>
                    <td>4</td>
                    <td>Supriya</td>
                    <td>riya@gmail.com</td>
                    <td>User</td>
                    
                    <td>
                        <button class="action-btn edit-action">Edit</button>
                        
                    </td>
                </tr>
               
               
                <!-- More users can be added here -->
            </tbody>
        </table>
    </div>
</body>
</html>
