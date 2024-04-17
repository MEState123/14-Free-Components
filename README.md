# 14-Free-Components

This GitHub repository contains the 14 free components made using NEXT JS & Tailwind CSS Technologies.
Please provide suggestions as there is always room for improvement and as a new developer I would love to hear suggestions and improvement feedback

It contains the following 14 components:

1 Info Card

2 Login Form

3 Contact Form

4 Navbar | Header

5 Footer

6 Registration Form

7 Company Features Display

8 Company Features | Qualities (Extended)

9 Search Bar Component

10 Single Client Testimonial

11 Multiple Clients Testimonial

12 Vertically Arranged Testimonials

13 Faqs

14 Portfolio Showcase 

# Procedure

To set up first take the page.tsx file (it contains the actual Components) and place it in a suitable directory of your choice

*(Make sure that the entire next js environment is already setup and tailwind CSS is installed)* 

Import the components required in your workflow, *(The name of the component function is mentioned above)* 

One final thing to keep in mind is to import (copy and paste) all of the global.css data into your CSS file as some of the component's properties are set up using custom CSS

extend: {
      backgroundImage: {
        "gradient-radial": "radial-gradient(var(--tw-gradient-stops))",
        "gradient-conic":
          "conic-gradient(from 180deg at 50% 50%, var(--tw-gradient-stops))",
      },
      colors:{
        'custom-purple': '#380052',
        'custom-nav-color': "#5B006D",
      },
    },

add the custom colors like this for the components to work properly

To properly see some colors there are some specific custom colors that were defined in tailwind css config file so also make sure to update your tailwind css config file here it is:


To see the preview of the components please take the images folder and place it in the "src" directory and inside the "app" directory make a new root group place the Preview Folder inside the root group, then run the preview using "npm run dev" to see the Preview

# Procedure End


# Attribution | Warnings
*Please keep in mind that you can use these components both commercially and individually for free and there are no restrictions*
*Please keep in mind that the images and icons are obtained from the following websites*:
Images(Portfolio Website Images and other images): Vecteezy
Icons: Flaticon

# *Keep in mind that we are attributing the images to their respective creators and have no ownership rights, Please do not use these images unless you have the License & Permit to use them or At your own risk*
