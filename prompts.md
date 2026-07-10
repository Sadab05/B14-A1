1st prompt:I've attached an Ui picture. I'm actually making a landing page for Dev conference website, and in the bottom it tells me to create a suitable section with Ai, well i dont want you to generate codes for me, instead i want you to suggest me some section that would go well with the theme of this website. and it would be great if i can get a visual representation of each section you recommend me.


2nd Prompt: I want to go with the conference schedule, can you further explain the layout, and what should be inside this section, make sure everythings goes with the theme

3rd Prompt: can you generate an image of the section


4th prompt: i have given you day 1 unordered list structure now write me day 2 and day 3 using the same structure and same tags

<ul>
    <li>
        <h4>09:00 - 10:00</h4>
        <h3>Opening Keynote</h3>
        <p>The future of software development and innovation.</p>
    </li>
    <li>
        <h4>10:30 - 11:30</h4>
        <h3>AI in 2026: Trends & Beyond</h3>
        <p>Explore the next generation of AI and machine learning.</p>
    </li>
    <li>
        <h4>12:00 - 01:00</h4>
        <h3>Lunch Break</h3>
        <p>Enjoy lunch while networking with fellow developers.</p>
    </li>
    <li>
        <h4>01:30 - 02:30</h4>
        <h3>Building Modern Web Apps</h3>
        <p>Best practices for creating fast and scalable web applications.</p>
    </li>
    <li>
        <h4>03:00 - 04:00</h4>
        <h3>Scalable APIs with Node.js</h3>
        <p>Learn techniques for designing reliable backend services.</p>
    </li>
    <li>
        <h4>05:00 - 06:30</h4>
        <h3>Networking Mixer</h3>
        <p>Connect with speakers, recruiters, and fellow attendees.</p>
    </li>
</ul>

5th prompt: i want everything inside the list in a div. every h4,h3 and p will be inside one div

<div class="schedule-cards">
<!-- card 1 -->
<div class="schedule-card-design">
    <div class="schedule-card-top">
        <span class="icon"><i class="fa-regular fa-calendar"></i></span>
        <div>
            <h4>Day 1</h4>
            <h3>Oct 20, 2026</h3>
            <p>AI and Innovation</p>
        </div>
    </div>
    <hr>
    <ul>
        <li>
            <h4>09:00 - 10:00</h4>
            <h3>Opening Keynote</h3>
            <p>The future of software development and innovation.</p>
            <span class="icon"></span>
        </li>
        <li>
            <h4>10:30 - 11:30</h4>
            <h3>AI in 2026: Trends & Beyond</h3>
            <p>Explore the next generation of AI and machine learning.</p>
        </li>
        <li>
            <h4>12:00 - 01:00</h4>
            <h3>Lunch Break</h3>
            <p>Enjoy lunch while networking with fellow developers.</p>
        </li>
        <li>
            <h4>01:30 - 02:30</h4>
            <h3>Building Modern Web Apps</h3>
            <p>Best practices for creating fast and scalable web applications.</p>
        </li>
        <li>
            <h4>03:00 - 04:00</h4>
            <h3>Scalable APIs with Node.js</h3>
            <p>Learn techniques for designing reliable backend services.</p>
        </li>
        <li>
            <h4>05:00 - 06:30</h4>
            <h3>Networking Mixer</h3>
            <p>Connect with speakers, recruiters, and fellow attendees.</p>
        </li>
    </ul>
</div>
<!-- card 2 -->
<div class="schedule-card-design">
    <div class="schedule-card-top">
        <span class="icon"><i class="fa-regular fa-calendar"></i></span>
        <div>
            <h4>Day 2</h4>
            <h3>Oct 21, 2026</h3>
            <p>Cloud and DevOps</p>
        </div>
    </div>
    <hr>
    <ul>
        <li>
            <h4>09:00 - 10:00</h4>
            <h3>Cloud Native Applications</h3>
            <p>Learn how modern cloud architectures improve scalability.</p>
        </li>
        <li>
            <h4>10:30 - 11:30</h4>
            <h3>Docker & Kubernetes Deep Dive</h3>
            <p>Master containerization and orchestration for production.</p>
        </li>
        <li>
            <div>
                <h4>12:00 - 01:00</h4>
                <h3>Lunch Break</h3>
                <p>Recharge and connect with fellow cloud professionals.</p>
            </div>
            <span class="icon"></span>
        </li>
        <li>
            <div>
                <h4>01:30 - 02:30</h4>
                <h3>CI/CD Best Practices</h3>
                <p>Automate testing and deployment with modern DevOps tools.</p>
            </div>
            <span class="icon"></span>
        </li>
        <li>
            <div>
                <h4>03:00 - 04:00</h4>
                <h3>Hands-on DevOps Workshop</h3>
                <p>Build and deploy a real-world application from scratch.</p>
            </div>
            <span class="icon"></span>
        </li>
        <li>
            <h4>05:00 - 06:30</h4>
            <h3>Community Meetup</h3>
            <p>Exchange ideas and network with developers and experts.</p>
        </li>
    </ul>
</div>
<!-- card 3 -->
<div class="schedule-card-design">
    <div class="schedule-card-top">
        <span class="icon"><i class="fa-regular fa-calendar"></i></span>
        <div>
            <h4>Day 3</h4>
            <h3>Oct 22, 2026</h3>
            <p>Career and Future</p>
        </div>
    </div>
    <hr>
    <ul>
        <li>
            <h4>09:00 - 10:00</h4>
            <h3>Building Your Developer Career</h3>
            <p>Essential skills, mindset, and strategies for long-term success.</p>
        </li>
        <li>
            <div>
                <h4>10:30 - 11:30</h4>
                <h3>Open Source: Make an Impact</h3>
                <p>Learn how contributing to open source accelerates your growth.</p>
            </div>
            <span class="icon"></span>
        </li>
        <li>
                <h4>12:00 - 01:00</h4>
                <h3>Lunch Break</h3>
                <p>Enjoy lunch while meeting speakers and fellow attendees.</p>
        </li>
        <li>
            <h4>01:30 - 02:30</h4>
            <h3>Startup Showcase</h3>
            <p>Discover innovative ideas and products from emerging startups.</p>
        </li>
        <li>
            <h4>03:00 - 04:00</h4>
            <h3>Ask the Experts Panel</h3>
            <p>Get practical advice from experienced engineers and founders.</p>
        </li>
        <li>
            <h4>05:00 - 06:30</h4>
            <h3>Closing Keynote</h3>
            <p>A look at the future of technology before the conference concludes.</p>
        </li>
    </ul>
</div>

6th prompt: i dont need to add another class, since im only doing this so the this containers immediate parent can flex