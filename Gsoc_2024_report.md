# GSoC 2024 Report

**Author**: [Aditya Sharma](https://github.com/your-github-profile)

**Organization**: [Keploy](https://www.keploy.io/)

**Project**: [Keploy UI Console & Webstories](#)

## Mentors

- [Shubham Jain](https://www.linkedin.com/in/slayerjain/)
- [Neha Gupta](https://www.linkedin.com/in/neha-gup/)
- [Charan Kamarapu](https://www.linkedin.com/in/charan-kamarapu/)
- [Hermione Dadheech](https://www.linkedin.com/in/hermione-dadheech/)

## Project Description

Writing unit test cases can be challenging and sometimes inefficient. Keploy streamlines this process by creating backend API tests with built-in mocks or stubs, recording your application's network calls to make testing faster and more efficient than traditional unit tests.

This project focuses on developing a console for Keploy that allows users to gain hands-on experience with the platform. The console enables users to capture test cases, replay them, and test with their preferred libraries, all within an interactive and user-friendly environment. Additionally, the console includes an integrated terminal for logs, providing real-time insights into the testing process. To keep users informed, the console also features web stories that provide the latest updates and news about Keploy.

## My Contribution to Keploy (GSOC-Project)

I undertook the challenge of developing key components for Keploy, specifically the **WebStories** feature and the **Keploy UI Console**.

### WebStories
I developed the WebStories feature , for displaying web-stories related to the testing and keploy. This involved:
- Designing and developing the UI components.
- Managing the states to work synchronously with images. 

PRs:
- [Webstories-1](https://github.com/keploy/website/commit/26542e6c744893c7465acc4f104a2920b383ce8a)
- [Webstories-2](https://github.com/keploy/website/pull/66)

### Keploy UI Console
I also worked on enhancing the Keploy UI Console, focusing on improving user interaction and interface design, which included:
- Streamlining the console layout for better user experience.
- Integrating the keploy software using the graphql queries. Fetching the real-time logs from the backend. Displaying in the terminal.

PR:
- [Keploy UI Console](https://github.com/keploy/website/pull/42)

## Completed Tasks

### `Major Contributions`:

- **Authors Page Feature**: Implemented a feature to display the Authors Page.
  - **Related PR**: [#7 (Keploy-BlogWebsite)](https://github.com/keploy/blog-website/pull/7) - **Status**: Merged

- **Fix Tags and Adding Tags**: Resolved a bug related to tags and added the ability to manage tags.
  - **Related PR**: [#25 (Keploy-BlogWebsite)](https://github.com/keploy/blog-website/pull/25) - **Status**: Merged

- **Table of Contents Feature**: Developed a feature to include a Table of Contents.
  - **Related PR**: [#13 (Keploy-BlogWebsite)](https://github.com/keploy/blog-website/pull/13) - **Status**: Merged

- **Author Profile Feature**: Added functionality to display detailed Author Profiles.
  - **Related PR**: [#19 (Keploy-BlogWebsite)](https://github.com/keploy/blog-website/pull/19) - **Status**: Merged

### `Minor Contributions`:

- **Code Highlight Feature**: Implemented a feature to highlight code snippets.
  - **Related PR**: [#10 (Keploy-BlogWebsite)](https://github.com/keploy/blog-website/pull/10) - **Status**: Merged

- **Meta Tag Bug**: Fixed a bug related to meta tags.
  - **Related PR**: [#9 (Keploy-BlogWebsite)](https://github.com/keploy/blog-website/pull/9) - **Status**: Merged

- **CodeBlocks Feature**: Added and improved code block features.
  - **Related PRs**: [#338 (Keploy-Docs)](https://github.com/keploy/docs/pull/338), [#341 (Keploy-Docs)](https://github.com/keploy/docs/pull/341) - **Status**: Merged

- **URLs Bug**: Resolved a bug related to URLs in the blog-website.
  - **Related PR**: [#17 (Keploy-BlogWebsite)](https://github.com/keploy/blog-website/pull/17) - **Status**: Merged

## Future Tasks

- **Enhancing Console Efficiency and Web Stories**: I plan to work on improving the efficiency of the Keploy console and the web stories feature, making them more responsive and user-friendly.

- **Expanding Language Support**: I aim to extend the functionality of Keploy by adding support for more programming languages, starting with Java. This will make the tool more versatile and accessible to a broader range of developers.

## Challenges and Takeaways

Working on the Keploy console project was both challenging and rewarding. From the outset, I delved deep into understanding the intricacies of integrating real-time logging, enhancing user experience with interactive web stories, and ensuring seamless API test case management. These features demanded a thorough understanding of front-end technologies, which I developed through hands-on experience.

One of the key challenges was optimizing the console's efficiency while maintaining a user-friendly interface.
This project honed my skills in problem-solving, efficient coding, and UI skills. My ability to write clean, maintainable code improved significantly, as did my understanding of how to design a robust and scalable application. The feedback and guidance from my mentors were invaluable in helping me overcome obstacles and achieve the project’s goals with high quality.

## Related Blogs

[WIP]

## Acknowledgements

I would like to extend my deepest gratitude to all my mentors for their unwavering support throughout this project. A special thanks goes to [Neha Gupta](https://www.linkedin.com/in/neha-gup/) for her invaluable guidance in helping me truly understand what excellent UI design entails and for her continuous support throughout the GSoC journey.

I also want to acknowledge [Charan Kamarapu](https://www.linkedin.com/in/charan-kamarapu/) and [Hermione Dadheech](https://www.linkedin.com/in/hermione-dadheech/) for their exceptional guidance and mentorship throughout the GSoC period. Contributing to Keploy has significantly accelerated my learning curve, and I will always be grateful for the opportunity to be a part of this amazing community.

**Thank you, Keploy, for an unforgettable experience and for helping me grow as a developer!**
