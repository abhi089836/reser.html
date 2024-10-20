<html>
<head>
    <link rel="stylesheet" href="restaurant.css"/>
	<link rel="stylesheet" href="reservation.css"/>
	 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Reservation | Abhi Restaurant</title>
</head>
<body>
    <div-main>
          <div-nav1>
		    <a href="#">Home</a>
            <a href="menu.html">Menu</a>
            <a href="#">Reservation</a>
            </div-nav1>
      
      <div1>
        <h2>Abhi Restaurant</h2>
      </div1>
     <div-nav2>
      <div-search>
        <input type="text"placeholder="Search...">
        <i class="fa-solid fa-magnifying-glass"></i>
      </div-search>
      
      <div-user>
            <i class="fa-solid fa-user"></i>
            <a href="loginPage.html"><span>User</span></a>
      </div-user>
    </div-nav2>
   
   </div-main>
   
   <div-reservation-container>
          <div-reservation> 
		     <center><form>
	               <h2>Your Reservation</h2>
                   <div7> 
				        <input type="text" placeholder="Your Name">
						 <input type="email"placeholder="Your Email">
				    </div7>	
                    <div8>
                          <input type="date"placeholder="Choose date">	
						   <input type="time"placeholder="Choose time">
					</div8>	
                    <div9>
					      <textarea placeholder="Your request"cols="30"rows="7"></textarea>
					</div9>	
                    <div10>
					       <a-btn href="#">Book Now</a-btn>
					</div10>					
	 		 </form></center>
		  </div-reservation>
  </div-reservation-container>
   
  
</body>
</html>
