# ee5178-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [EE5178 Assignment 4 Solved](https://www.ankitcodinghub.com/product/ee5178-modern-computer-vision-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110185&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE5178 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Programming Assignment 4: Panoramic Stitching

Instructions

1. Please use moodle discussion threads for posting your doubts.

2. Before posting any question, check if the same question has been asked earlier.

3. Submit a single zip file in the moodle named as PA4 Rollno.zip containing the report and folders containing corresponding codes.

4. Read the problem fully to understand the whole procedure.

5. Comment your code generously.

6. Put titles to all of the figures shown.

7. Save your iPython notebook as an html file with all the figures and results and submit it along with the iPython notebook containing your code.

Panoramic Stitching

(a) Image pair (b) Stitched panorama

Figure 1: Panorama produced using our implementation.

1

Tasks

1. Implement get features(img) to compute SURF/SIFT/ORB features for both of the given images. Implement match keypoints(desc1, desc2) to compute key-point correspondences between the two source images using the ratio test. Run the plotting code to visualize the detected features and resulting correspondences.

Hint: You can use existing libraries.

2. Write a function find homography(pts1, pts2) that takes in two N × 2 matrices with the x and y coordinates of matching 2D points in the two images and computes the 3 × 3 homography H that maps pts1 to pts2. You can implement this function using direct linear transform (DLT). Report the homography matrix.

Note: You should implement this function on your own.

3. Your homography-fitting function from (2) will only work well if there are no mismatched features. To make it more robust, implement a function transform ransac(pts1, pts2) that fits a homography using RANSAC. Run the plotting code to visualize the point correspondences after applying RANSAC. Note: You should implement this function on your own.

4. Write a function panoramic stitching(img1, img2) that produces a panorama from a pair of overlapping images using your functions from the previous parts. Run the algorithm on the two images provided. Report the panorama stitched image.

Note: You should implement this function on your own. Use inverse mapping while stitching.

5. Extend the algorithm to handle n = 3 images, use these given images. We have also provided a reference panoramic stitched image to compare your result with. Report all visualizations as mentioned for n = 2 case, along with two homography matrices with respect to the center image.

Note: You should implement this function on your own. Take the center image as the reference and find the homography transformations with respect to this center image, which doesn’t need further transformations and also produces the most aesthetically pleasing panorama.

–end–

2
