<link rel="stylesheet" href="../../style.css">

## Question
Instructions: Read Dicheva & Hodge (2018). Think about an online system which you use on a daily basis.Consider how it might operate at the back-end using data structures. This will inform our discussion during next week’s seminar.


## Answer:

Below are two common systems used on daily bases on the web and how they would work internally in a data structure<br>

<div class="container" aline="left">  
    <div class="text-section"aline="left"> 
<p>
<b>User Data Management:</b><br>
User data, such as usernames, email addresses, and passwords, would be stored in a database, likely using a hash table or a balanced binary search tree for efficient lookup and retrieval.
</p> 
    </div>  
    <div class="image-section" aline="right">    
        <img src="static/user.jpg" width="275"/>
    </div> 
</div>

<div class="container">  
    <div class="text-section"> 
<p>
<b>Likes, Retweets, and Comments:</b><br>
Each interaction on a tweet (like, retweet, comment) needs to be recorded and associated with the respective tweet. This information can be stored in separate data structures like sets or lists to track engagements and ensure uniqueness.
</p> 
    </div>  
    <div class="image-section">    
        <img src="static/like.png" width="275"/>
    </div> 
</div>

<div class="container">  
    <div class="text-section"> 
<p>
<b>Notifications:</b><br>
To keep users informed of interactions, notifications need to be managed. These can be stored in a priority queue, where each notification has a timestamp, and the queue is sorted based on priority.
</p> 
    </div>  
    <div class="image-section">    
        <img src="static/notification.png" width="275"/>
    </div> 
</div>