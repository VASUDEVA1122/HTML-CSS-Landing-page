14. Zerodha Landing Page (Part 2)
<br></br>
In this project, I continued building a Zerodha-inspired landing page and explored key CSS styling techniques:

Color: Applying text and background colors.
<br></br>
Background: Customizing the background of elements.
<br></br>
Border & Border-Radius: Styling element borders and adding rounded corners.
<br></br>
Padding/Margin: Managing spacing inside and around elements.
<br></br>
Box Shadow: Adding depth to elements with subtle shadows.
<br></br>
Flexbox: Positioning and aligning elements effectively.
<br></br>
Most used properties:
justify-content: center: Centering elements within a container.
justify-content: space-between: Distributing elements evenly across the page.
<br></br>
Current Progress
We now have a simple, visually appealing landing page with the following layout:

Code-
<div style="display:flex;
justify-content: space-between;
padding-left: 100px; 
padding-right: 100px;
box-shadow:2px 1px 2px #eee ">
<img src="logo.svg" width="120" height="20px"
style="padding-top: 20px;" />
<div style="display: flex;">
         <div style="padding: 20px; color: #666; cursor: pointer; ">
            Signup
        </div>
        <div style="padding: 20px; color: #666; cursor: pointer; ">
            About
        </div>
        <div style="padding: 20px; color: #666; cursor: pointer; ">
            Product
        </div>
        <div style="padding: 20px; color: #666; cursor: pointer; ">
            Pricing
        </div>
        <div style="padding: 20px; color: #666; cursor: pointer;">
            Support
        </div>
 </div> 
</div>

<br />
<div style="display: flex; justify-content: center; padding-top: 20px ">
         <img src="photo.png" width="1000" />
</div>

<div style="padding-top: 40px; display: flex; justify-content: center;">
    <h1 style="font-weight: 500; font-size: 40px;">Invest in everything</h1>
</div>

<div style="padding-top: 2px; display: flex; justify-content: center;">
    <h2 style="font-weight: 400;">Online platform to invest in stocks, derivatives, mutual funds, ETFs, bonds, and more.</h2>
</div>


<div style="display: flex; justify-content: center; cursor: pointer; padding-top: 10px; ">
    <div style="background-color: #387ed1; padding: 10px 30px; color: #eee; border-radius: 3px; font-size: 1.2em; ">
        Sign up for free
    </div>
</div>

<br></br>

How It Looks
<br></br>
The page includes:

A navigation bar with links (Signup, About, Product, Pricing, Support).
<br></br>
A hero section featuring an image, title ("Invest in everything"), and a subtitle.
<br></br>
A call-to-action button: "Sign up for free."
<br></br>
Feel free to check out the code and suggest improvements! 🚀
