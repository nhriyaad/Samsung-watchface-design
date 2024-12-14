# Samsung-watchface-design

# How to Create a Stunning Watch Face Using Tag Expressions

Watch Face Studio, developed by Samsung, is a powerful tool that allows designers to create custom watch faces for Wear OS smartwatches. It is user-friendly and enables both beginners and experienced developers to build unique, interactive, and functional watch faces without any coding knowledge. One of the standout features of Watch Face Studio is Tag Expressions, which lets you introduce dynamic and context-aware elements. In this blog, we’ll guide you through creating an analog watch face using Tag Expressions, showing battery levels dynamically and adding color-changing effects based on conditions.

**What Are Tag Expressions?**

Tag Expressions are logical constructs used in watch face design to manipulate and control how elements behave based on specific conditions. By combining static values, system tags, and conditional logic, you can create dynamic behaviors such as animations, progress indicators, and interactive components.

For instance, you can:

Show or hide elements based on battery levels.

Create progress bars for various indicators.

Change colors or text dynamically.

Setting Up Your Project

To get started, you’ll need:

Watch Face Studio: Download and install the latest version of Watch Face Studio from the Samsung Developers website.

Design Assets: Prepare your visual assets like background images, hands for the analog watch, and icons.

This project builds on Task 1, where we created a static analog watch face with watch hands and battery level indicators.

Step-by-Step Guide to Creating a Watch Face Using Tag Expressions

**Step 1: Create a New Analog Watch Face**

Open Watch Face Studio and start a new project.
![image](https://github.com/user-attachments/assets/6d168acf-2ed1-47e1-954a-1534f0535d79)


-Give a name to your project. chose type "watchface" and select Default screen size and click OK
- now Add the basic elements for an analog watch, including: Hour, minute, and second hands.
by clicking on + icon on top then select analogue clock this will add Hour, Second and minute hands to the watch.
- You can change the hand type by right clicking hand element then choosing swap media.
  ![image](https://github.com/user-attachments/assets/a589ceb8-c30f-4f0e-b5b7-f9564400fdf2)

- now to add a cool background for the watch you can just click the + icon again then select image and choose any of the sample or custom image for your watch.
  ![image](https://github.com/user-attachments/assets/7e88fc9b-1c54-49ab-bcfa-aa4e74f12c81)
- for adding index click on + icon then choose index from index images choose any one you want.
  ![image](https://github.com/user-attachments/assets/a782f266-c18d-4735-b2f4-61fec0e6b8f2)
- You can add date to your watch by clicking ICU date & time and change the formatting type from properties to give your watch date a better look.
  ![image](https://github.com/user-attachments/assets/84ed2cb2-873b-4412-a7b6-dd8fc12579dc)

-  
  


A battery level indicator.

**Step 2: Add Dynamic Battery Level Indicator**

Display the Battery Level

- For battery level Add a Cicrcle element by clicking + icon then Circle. You can choose line or text also if you want.
- From Properties choose Default Provider watch battery
  ![image](https://github.com/user-attachments/assets/de3f0f30-4fff-4529-99c1-df0c1f9982c6)
- For short text choose any design
  ![image](https://github.com/user-attachments/assets/d33c9d8b-daee-4c84-9d27-2c90792322bd)
- Then scroll down to Text portion and type [BATT_PER] in the box Test text. We are using Tag Expressions to get battery percentage of the watch.
  ![image](https://github.com/user-attachments/assets/2646c43c-1550-426d-b68f-95ac1406d6a1)
- then click on layer and right click on battery layer named circle complication
  ![image](https://github.com/user-attachments/assets/40c672f0-1276-4752-b67c-8219284b7240)
- then goto layer circle complication copy and change the copy layer color red
- Now click on Add conditional line and select battery then choose circle complication copy layer and double click in each of the element such as(title copy,text copy, icon copy,progress bar copy) in time frame then press ok for each.
  ![image](https://github.com/user-attachments/assets/25a36b65-be7f-409e-abf7-3effa0996785)

- then there will be a progress bar adjust it to 0-20% for all the 4 elements.
  ![image](https://github.com/user-attachments/assets/1dfff56e-63e8-43be-af3c-d37e86ae8929)
- Then choose choose circle complication layer and double click in each of the element such as(title copy,text copy, icon copy,progress bar copy) in time frame then press ok for each.
- For circle complication layer adjust those progress bar to 21%-100%
  ![image](https://github.com/user-attachments/assets/7917f020-37bb-4e84-b926-5e3c4385b2ee)
- Great now our battery indicator is ready. Now you can select show/hide run and move the battery percent scroller to check ur battery indicator will show red when its <=20%
  ![image](https://github.com/user-attachments/assets/7a1fbe9c-e557-4bd1-befd-49f400a07837)

- Now to add hour number to the clock you can add another image to the clock just by clicking + icon and the selecting image then choose index with number from sample.or You can desing your own.
  ![image](https://github.com/user-attachments/assets/85f5fc29-c937-4f1e-a829-7fb10ae68a9b)

Use Watch Face Studio’s preview mode to test how the battery indicator and color changes function.

**Final Thoughts**

Tag Expressions empower you to create watch faces that are not only visually stunning but also functionally rich. By following this guide, you’ve created an analog watch face that dynamically displays the battery level and visually alerts users with a color change when the battery is low. This is just the beginning—experiment further to add animations, interactions, and other dynamic elements to your designs.

Ready to showcase your creativity? Dive into Watch Face Studio and share your amazing designs with the community!    
  
