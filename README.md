# Configuration
inside `config.json` make sure you update the value for `username`, `password`, `maxPages`, `keywords`, and `message`

`maxPages` refers to how many pages you want to look for the jobs you're looking for.

`keywords` refers to the keywords you're looking for in the job posting.

`message` refers to the message you're going to send to the job poster

>Subject is always "Applying for {job_title}"

## Message Templating
in `message` you can use the variables `contact_person` for job poster, `job_title` for the job title you're applying for.

I.E: 
>Dear {contact_person},\n\nWith my extensive experience and passion for excellence, I am confident that I can make a significant contribution to your team as {job_title}.\n Please take a moment to review my profile for more details on my qualifications and achievements.\n\nLooking forward to the possibility of working together.\n\nBest regards


here {contact_person} would be replaced by the job author's name and {job_title} would be replaced by the job title you are applyin for. <mark>be very careful</mark> of using `job_title` as sometimes it contains more than the job title itself.