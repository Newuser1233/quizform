# quizform

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>
   <form action="https://newuser1233.github.io/quizanimal/" method="GET">
       <div>
         <label for="name">Name</label>
         <input type="text" name="name" id="name" placeholder="username"
         required>
       </div>
       <div>
          <label for="email">Email</label> 
          <input type="email" name="email" id="email" required>
       </div>
       <div>
          <label for="age">Age</label> 
          <input type="number" name="age" id="age" required min="1" max="200">
       </div>
       <div>
           <label for="date">Date</label>
           <input type="date" name="date" id="date" required>
       </div>
       <div>
           Favorite Food
           <div>
               <label for="banana">Banana</label>
               <input type="checkbox" name="banana" id="banana">
           </div>
           <div>
               <label for="apple">Apple</label>
               <input type="checkbox" name="apple" id="apple">
           </div>
           <div>
              Gender 
           </div>
           <div>
            <label for="male">Male</label>
            <input type="radio" name="gender" id="male">
           </div>
           <div>
               <label for="female">Female</label>
               <input type="radio" name="gender" id="female">
           </div>
          <div>
         <label>
             Password
             <input type="password" name="Password" required>
            </label>
           </div>
           <button type="reset">Reset</button>
           <button type="sumbit">Submit</button>
 
