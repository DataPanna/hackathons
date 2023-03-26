# Preparing for Hackathons
If you are going to attend a hackathon, you can get more from the experience by doing a bit of prep work. Hopefully each hackathon will be unique, but there are some common steps involved with most of them.

## Research Projects
Hackathons generally have a common theme that connects a variety of open data sets, and attendees divide into groups of various skill levels and backgrounds to tackle projects based on that theme. You will typically find starter ideas for projects on the hackathons website or communications. You don't always have to sign up for a project ahead of time, but thinking about what types of problems you'd like to solve or what data you'd like to look at is a great way to get informed and excited about the event.

## Choose a Role
One of the best parts of hackathons is being able to participate in a cross section of minds motivated to solve real-world problems. Community Organizers, Technologists, Artists, Educators, Government Leaders, and more come together to use modern technology to bring innovation and inclusion to the places its needed most. Whether you are a seasoned hackathon attendee or new to such events, you should be able to find a role that fits your skills and interests. Using the same advice about researching projects ahead of time from above, you can hopefully get a sense for what types of scenarios the different projects need. Typically, job roles like Product/Project Manager, Subject Matter Expert, Data Engineer/Analyst/Scientist, Designer, and Software/DevOps Engineer are common, but the atmosphere should be flexible and open to accomodating the unique perspective you can bring to the event.

## Ready Gmail Account
In the world of hackathons, there are a few common platforms used as a primary means of collaboration. Without a doubt, the most frequently used is Google Drive. Many times hackathon materials are distributed via Google Docs and work groups at the event will spin up smaller shared folders to store discussion notes, design mock-ups, and anything else. What's even more important, services like Gmail are easily accessible and provide a simple entry point for new participants. While you'll be able to get a lot out of a hackathon without a Gmail account, having one created specifically for hackathon use is a great idea. You can use this Gmail account to sign up for the event, to create sites on any websites linked as resources, and to share content during the Hackathon. Sure it's not open source, but it's a free resource made available to citizen developers working on usually no budget--leveraging free, commerical services is a reality most Hackathons must live with for the time being. For those able to support other options, kudos :)

## Ready Slack Account
Like Gmail, Slack is a fairly universally accepted tool at hackathons. Slack is a chat application that allows hackathon organizers a place for all participants to digitally communicate. Typically, the hackathon will have a Slack Workspace with channels for the primary projects explored during the event. Look on the hackathon website for any information as conversations sometimes start days before the event in Slack. It's very simple to sign up, and including your photo to your profile will help your team members know you better.

## Ready GitHub Account
Another important tool leveraged for hackathons is GitHub, a social code platform used to organize programming projects and coordinate contributions from distributed teams. Whether you are planning on committing code, documentation, or ideas as a result of your efforts, GitHub is likely the final place your work will live. Even if your results ultimatley show on a website, the code and content behind that website will almost certainly be stored on GitHub. There are definitely interesting exceptions, but the accessibility of the GitHub platform makes it a common choice amongst hackathon organizers. Here are some key notes about leveraging GitHub:
  - Keep Personal and Professional Accounts Separate (if you already have a work account)
  - setup global git name and email on your computer (if git isn't installed, go to [the git homepage](https://git-scm.com/) to determine how to install on your computer)
    - ```git --global --list```
    - if you don't see entries for user.name and user.email, use ```git user.name "Your Name"``` and ```git user.email "your.email@email.com"``` to set them
  - [Configure SSH](https://github.com/DataPanna/hackathons/blob/main/configure-ssh.md)
    - SSH is used to authenticate with the GitHub service; this step (or using a login) lets GitHub know you are allowed to submit your contribution and that no one is impersonating you
    - you don't need SSH to use GitHub (you can just use your GitHub login), but it's a great way to learn more about computer science!
    - if using multiple git logins, configure ssh hosts (advanced scenario)
  - Configure GPG (advanced scenario)
    - similarly to SSH, GPG is another security-forward mechanism for proving to others your contributions are your own
    - instead of focusing on authentication at the time of the commit, GPG leaves a permanent signature on each of your commits that lets others know it's cryptographically verified
    - while this step is not required for most participants, if you will be contributing code to a product that will go into production, consider this necessary
  - Setup repos based on expected role
    - If you are able to find data or topics you can perform some work on ahead of time, create a repo in your new GitHub account. It will help you get familiar with what to expect at the event
    - default branch should be called main or similar
    - enable branch protection that requires pull requests
