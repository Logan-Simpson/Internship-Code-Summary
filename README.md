# Internship-Code-Summary
OVERVIEW:
  This is my project I worked on for my internship with Prosper IT Consulting.  The main page is a Lifestyle site with links to various hobbies, activites, and interests.  My job was to create a lifestyle page that branched off of the main/home page.  

TASKS/APPROACH:  
  The link I developed is the Yoga page.  I was assigned stories/tasks to complete by my project manager.  For this project all the code was written in VS Code, with HTML, CSS, Bootstrap and JS.  I used Azure DevOps and Slack to collaborate with other team members for this project and to connect with my project managers.  First I decided what the main sections of the page would be and how I wanted the layout to look.  I also wanted the color scheme to be soothing/zen because it's about yoga, which is how I decided on the color scheme.  I started with a basic HTML skeleton and added bootstrap componenets to that.  After I got the basic layout working, I added in the images and CSS styling to it. 

SUMMARY:  
  This work was done in a two week sprint.  The project managers held daily standups to discuss what I worked on and any roadblocks I had.  On Mondays we held sprint planning sessions and on Fridays we held a daily standup as well as a sprint retrospective.  This was such a great experience that really got me familiar and comfortable working with a team and using Azure and Git. The process got me comfortable with starting a design from the ground up and helped me figure out how I like to approach building a site.  It was a great experience.  I had a couple roadblocks in styling the pop-up form and getting all the elements of the pop-up form to be properly placed and looking good, my project managers helped me figure that out and gave me good ideas for that. 
  
![Screenshot (7)](https://user-images.githubusercontent.com/71109424/111341569-e13a9180-8636-11eb-97d2-3d6712d76449.png)
![Screenshot (8)](https://user-images.githubusercontent.com/71109424/111341599-e4ce1880-8636-11eb-86e6-00ebfe7c4be7.png)
![Screenshot (10)](https://user-images.githubusercontent.com/71109424/111341618-e8fa3600-8636-11eb-8cc5-2fa465689a89.png)



<!--Some code snippets-->

<div class="modal fade" id="staticBackdrop" data-backdrop="static" data-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="staticBackdropLabel">Yoga Newsletter</h5>
          
        </button>
      </div>
      <div class="modal-body">
       
        <!--Form inside modal-->
       
        <form
          action="https://formspree.io/f/xvovddyq" method="POST">
          <div class="form-row align-items-center">
            <div class="col-sm-5 my-1">
              <label class="sr-only" for="inlineFormInputName">First Name</label>
              <input type="text" class="form-control" id="inlineFormInputName" placeholder="Jane">
            </div>
            <div class="col-sm-5 my-1">
              <label class="sr-only" for="inlineFormInputName">Last Name</label>
              <input type="text" class="form-control" id="inlineFormInputName" placeholder="Doe">
            </div>
            <div class="col-sm-10 my-1">
              <label class="sr-only" for="inlineFormInputName">Email</label>
              <input type="text" name="_replyto" class="form-control" id="inlineFormInputName" placeholder="Email">
             </div>
                <div class="col-sm-5 my-1">
                  <label class="sr-only" for="inlineFormInputName">Phone</label>
                </div>
                <input type="text" class="form-control" id="inlineFormInputName" placeholder="Phone">
              </div>
            </div>
            
            <div class="col-auto my-1">
              <div class="form-check mb-2">
                <input class="form-check-input" type="checkbox" id="autoSizingCheck2">
                <label class="form-check-label" for="autoSizingCheck">
                  I agree to Terms of Use & Privacy Policy
                </label>
              </div>
              <div class="form-check mb-2">
                <input class="form-check-input" type="checkbox" id="autoSizingCheck2">
                <label class="form-check-label" for="autoSizingCheck">
                  I agree to receiving emails
                </label>
              </div>
            </div>
            
            <div class="col-auto my-1">
              <button type="submit button" class="btn btn-primary newsBtn">Submit</button>
              <button type="button" class="btn btn-secondary closeBtn" data-dismiss="modal" aria-label="Close">Close</button>
            </div>
            <br>
          </div>
      </div>
      
      <div class="modal-footer">
      </div>
    </form>
    </div>
  </div>
</div>
<br>
<br>
