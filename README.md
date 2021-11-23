# Buffer_Overflow_Attack
In this program I have tried to demonstrate Buffer Overflow Attack.
In this program you have to givw your input that is percieved by as system as your unique password, Your real password is JaiHind .

Now we have three cases:

1.now if you write a wrong password which have characters less than or equal to 10, it will show you that you have written a wrong password, and system wont give you admin access. 
2. In this case you'll write correct password and get system acces.
3. In this case if you'll write wrong password but if your password's length is more than 10, then it'll will show you wrong password but system will give you admin access.

It's happening because of gets() method which wont check if your input have more characters than your input, other problem is strcmp(), you can use strncmp() instead.

Thanks For Reading, find more about it on Google.
