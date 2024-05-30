Learning Management System (MERN stack)

Home Page: 

             1. Dark theme & Light theme 
             2. Admin can update the image & text on the homepage by going to the  
                  customization->Hero option in the Admin dashboard 
            3. can update our FAQs. We can edit the text, answer, delete it, or add a 
                 new one.
           4. We can update the course category
           5. Course listing
           6. Review feedback
           7. Footer
          8. Mobile responsive

Authentication:

1.Login -> using formic & yap form validation for this form 
2. We have both social authentication & manual authentication
3. After signing up you will get Verify your account using OTP, a pop which tells you to please check your mail to activate your account. 
4. We will send dynamic templates to your mail, not only for authentication but also for validation, asking questions, and admin replies, you will get mail all the time.
5. If you type the wrong OTP, a pop will come up saying invalid authentication code and will appear as red.
6. When you type OTP in your box, the cursor will automatically move to the next box, you don’t need to click on the next row.
7. When you click on verify OTP, a pop will come saying account verified
8. Now you can log in successfully.

User’s profile:

My Account: 
             1. Add/update/edit/delete profile picture, name, email address
2. Change Password
3. Enrolled Courses: when you click on  this will directly go to course access page
4.Log out



Course Page:

1.If you haven’t purchased the video you won’t get all the information e.g. video URL, video source code
2.Highly protected
3.For video play, we will use a platform named Video Cipher which platform is giving us JRM encryption. Using this encryption in this video player you cannot record this video or take screenshots, you cannot download this video.
4.Users can order the course by clicking on Buy this course
5.Users can pay with AfterPay, the US back cash app, a lot of payment gateway, and Gpay. We will implement a stripe element for this.



Admin Dashboard:

1. When users click on pay now, the admin will get an instant notification sound and message that a new order was placed.
2. Dashboard:
                                    1. Users Analytics
                                    2. Orders Analytics
              3. Sales obtained
              4. New Users
              5. Recent transactions

3. When users submit in Q&A or give some reviews about the course, the admin will get an instant notification with sound
4. The review notification will give a message with the user’s name and course details so the admin can go and reply to them.
5. Verified tick for admin only
6. Down to every video on the course access page we have four options
             1. Overview
             2. Resources
             3.Q&A
             4. Reviews
7. Data:
       1. Users
       2. Invoices: can download as CSV or print it


   
Content:
       1. Create Course: 
                        1. Course Information: course name, description, price, 
                                               estimated price,  tags, categories, level, 
                                            demo URL (after uploading the video to 
                                   video cipher we will get some ID just write that),  
                                      drag/drop thumbnail, or browse.
                       2. Course Options:  Benefits/prerequisites
                      3. Course Content:  Demo- video title, URL, length, 
                                   description, add link. There is a collapse option 
                                       or add new content & section
                     4. Course Overview
2. Live Courses: list of all courses and we can edit everything
3. Customization: Hero, FAQ, Categories
4. Controllers   
5. Analytics



Major Features:
1. Authentication
2. Layout
3. Course
4. Analytics
5. Orders
6. Notifications
