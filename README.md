# Internship-Code-Summary
This is what I worked on for my internship with Prosper IT Consulting.  The main page is a Lifestyle site with links to various hobbies, activites, and interests.  The link I developed is the Yoga page.  For this project all the code was written in VS Code, with HTML, CSS, Bootstrap and JS.  I used Azure DevOps and Slack to collaborate with other team members for this project and to connect with my project managers.  This work was done in a two week sprint.  The project managers held daily standups to discuss what I worked on and any roadblocks I had.  On Mondays we held sprint planning sessions and on Fridays we held a daily standup as well as a sprint retrospective. 
![Screenshot (4)](https://user-images.githubusercontent.com/71109424/110986281-539f2f00-8322-11eb-8ab0-cebbf4f2957c.png)
![Screenshot (5)](https://user-images.githubusercontent.com/71109424/110986474-8e08cc00-8322-11eb-9fb3-14198519ef20.png)
![Screenshot (6)](https://user-images.githubusercontent.com/71109424/110986662-c8726900-8322-11eb-9528-9c46829f346b.png)


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
