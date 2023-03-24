# Tennis-Club-Management
A simple Tennis Club Management program written in C that calculates the total amount that needs to be paid by the customers based on their membership status and the number of hours they have booked the court. It calculates the final due amount by providing various discounts to different tier members.

**#**Membership Levels and their discount percentages****
1. GOLD - 30% Discount
2. SILVER - 20% Discount
4. PLATINUM - 5% Discount

**#Hourly Cost** <br>
1000 per hour

**#Discount Calculation formula** <br>
1.GOLD MEMBERSHIP -<br>
<em> discount_amount=30*(1000*hours_spent)/100;    <br>
     discount_price=((1000\*hours_spent)-discount_amount);     <br> </em>
     
2.SILVER MEMBERSHIP - <br>
<em> discount_amount=20*(1000*hours_spent)/100;            <br>
     discount_price=((1000\*hours_spent)-discount_amount);      <br></em>
     
3.PLATINUM MEMBERSHIP - <br>
<em> discount_amount=5*(1000*hours_spent)/100;           <br>
     discount_price=((1000\*hours_spent)-discount_amount);          <br></em>
