# Mockup-for-a-project-of-degital-geograpies

## 1. Introduction

Mockups are essential for the design process at the early stage of a project as they give viewers an idea of how the final product will appear, and the implementation of interactive elements like buttons and icons also hints at the function. With a well-made sample in front of their eyes, stakeholders don’t have to rely so much on their imaginations. So, in this lab, we are going to learn how to use one of the most famous browser-based UI and UX design applications Figma to create mockups for a project.

The project we are designing the mockup for is called **Damron Guide: Seattle**, it is a website utilizing online maps to visually explore the Damron’s Travel Guide which specifies the spatial pattern and temporal changes of the LGBT related places. Especially, The evolving space of LGBTQ life in Seattle in the past five decades. For more information, you could visit this web site (check [here](https://damron.com/about-us)).

In this mockup, we will walk through the whole design process of the main GUI including the basemap, venues,  layer switcher, timeline and info panel. Then, we will add in some hover over functions, and finally give a brief intro to how to design user interfaces other than the desktop GUI, such as the mobile GUI.

## 2. Preparation

### 2.1 Registration

In this section, we will guide you to use your email to sign up and log into the figma website.

1. Head to Figma.com and click **Sign up** in the top right corner. Or, follow this [link](https://www.figma.com/signup) directly.

2. Enter your **Email address** and a unique **Password** in the field provided, then click the **Sign up** button to complete the process. You will be logged into your new Figma account immediately. Or if you have a Google account, you can sign up using Google's Single Sign-On (SSO) process.

3. Figma will send you an email to verify your account. Open the email, and click the **Verification** button to complete the process and log into your new Figma account.

4. Figma will provide an introduction to some basic functions.

### 2.2 Relevant Resources

This section will introduce some relevant resources you probably will need when designing your own mockup. Please make sure to download the Charts plugin, System design kits and Google Map UI design kits ahead as we will use them in the next design mockup section.

**Maps: base map**

- [Google maps](https://www.google.com/maps/)
  
- [Mapbox](https://www.mapbox.com/)
  
- [Leaflet preview](https://leaflet-extras.github.io/leaflet-providers/preview/)
  
**Charts: map, data interactions**

- [Charts plugin](https://www.figma.com/community/plugin/731451122947612104/Charts)

**Design kits: design theme, an integrative framework/solution to the design components.**

- [System design](https://www.figma.com/@materialdesign)

- [Google Map UI](https://www.figma.com/community/file/775789656970237137)

**Dummy text: placeholder for narratives.**

- [Lipsum](https://www.lipsum.com/)
  
## 3. Design Mockup

### 3.1 Main GUI

In this section, we will design the main user interface. We will need to firstly create a new page, then, add in the base map, venues inside the page. Finally, we could incorporate some other map features into the page such as the zoom button, map layer selection, timeline, heatmap toggle, and info panel. 

### New file

In this part, we will create a new file with the common desktop screen size presets. 

1. Click the **Plus** sign at the top right of the page to create a new file.

2. In the template window, under **Blank Presets**, check **Desktop** with default size of **1440 x 1024** as it is one of the most common screen sizes today.

![](/images/0.png)

3.Click the **Create File** button at the bottom of the window to create the file.

![](/images/1.png)

### Base Map

In this part, we will add the base map we chose to our page and enable the horizontal and vertical scrolling to it.

1. Download this map we provided down below or go to one of the **Map Resources** we provided above, take a screenshot of the map image you want to use.

![](/images/2.png)

2. **Cmd + Shift + K (Mac) / Ctrl + Shift + K (Windows)**  to open the import image window.

![](/images/3.png)

3. Select the map image you downloaded earlier from your computer in the window.


4. Click **Open** to open the image.


5. Click anywhere inside the new blank page to place it in the page.


6. At the left side of your screen, under **Layers**, click the **name of the image** you just imported to select it

![](/images/4.png)

7. **Cmd + R (Mac) / Ctrl + R (Windows)** to rename it to **"Map"**.

8. Inside the design bar at the right side of your screen, change the **W (Width)** of the map to **2500** to make the image large enough to cover the whole page.

![](/images/5.png)

9. At the top of the design bar, click **the second and fifth icon** from left to right to make the map align horizontally and vertically center inside the page.

![](/images/a.png) ![](/images/b.png)

10. At the left side of your screen, under **Layers**, click **Desktop - 1** to select the frame.

![](/images/6.png)

11. At the right side of your screen, select **Prototype** at the top row.

![](/images/7.png)

12. Under the **Overflow behavior**, the default should be Vertical scrolling, click the **drop down arrow** to switch it to **Horizontal and vertical scrolling**. This will enable the user to scroll the map both horizontally and vertically inside the page.

![](/images/8.png)

### Venues

In this part, we will add the venues to the map. In the urban LGBTQ+ space, there are many types of venues with different ways to categorize them. For this part, we will only separate the venues into two categories: men (blue) or women (purple) related places. We will add more info later in the hover over functions. 

1. At the right side of your screen, select **Design** at the top row.

2. Uncheck the **Clip Content** option to view part of the map that is outside the page.

![](/images/9.png)

3. Hit **O** on your keyboard, then click anywhere inside the map to create an ellipse.

4. At the right side of your screen under **Design**, change the **W (Width)** and the **H (Height)** to 10 to make the ellipse smaller.

![](/images/10.png)

5. Under **Fill**, change the color to **Blue (2F35CA)**.

![](/images/11.png)

6. Click the **Plus** sign right beside **Effects** to add a new effects.

7. The default new effect should be **Drop shadow**. Click the **sun icon ☀️** to open a window with more detailed effecting settings.

![](/images/12.png)

8. In the drop shadow setting window, set **X** to **0**, **Y** to **0**, **Blur** to **10**, **Spread** to **7**, and **color** to **Blue (2F35CA) 25%**.

![](/images/13.png)

9. **Cmd + C (Mac) / Ctrl + C (Windows)** to copy this ellipse, then **Cmd + V (Mac) / Ctrl + V (Windows)** to paste it. The copy should be generated at the exact location of your original ellipse. Use your mouse to **select and drag** it anywhere else in the map.

![](/images/14.png)

10. At the right side of your screen under **Fill**, change the new ellipse's color to **Purple (CA2FC4)**.

![](/images/15.png)

11. Click the **sun icon ☀** to open a window with more detailed settings.

12. In the drop shadow setting window, set the **color** to **Purple (CA2FC4) 25%**.

![](/images/16.png)

13. Using the same process, you could create as many ellipses as you want with different colors inside the map.

![](/images/17.png)

14. At the left side of your screen, under **Layers**, (!!! If any ellipse is outside the Desktop - 1 frame, you need to drag them down inside the Desktop - 1 frame) hold **Cmd (Mac) / Ctrl (Windows)** and click all the ellipses you just created to select them.

![](/images/18.png)

15. **Cmd + G (Mac) / Ctrl + G (Windows)** to make them into a group.

16. **Cmd + R (Mac) / Ctrl + R (Windows)** to rename the group to **"Venues"**.

![](/images/18.png)

! Remember to keep the Venues group above the map layer or the venues will be covered by the map.
