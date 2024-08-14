# Promptopia
Promptopia is a modern web application designed to facilitate the discovery and sharing of AI prompts built as part of the [Next.js 14 Course from JavaScript Mastery](https://www.youtube.com/watch?v=wm5gMKuwSYk)

![promptopia-main-image](https://github.com/user-attachments/assets/50323cd9-94e8-4807-8362-cf8066c6c9fb)
  
## 📚 Technologies Used

- Next.js
- MongoDB
- NextAuth
- TailwindCSS

## 🌟 Features

### Discover and Share AI Prompts
- Explore a variety of AI Prompts shared by the community
- Create and Share your own prompts

### Create Prompts
![promptopia-create](https://github.com/user-attachments/assets/c229d7e5-2f2a-4e37-9568-f648f00a5c09)

### Edit and Delete created Prompts
- Users have the ability to edit and delete their created prompts

### My Profile Page
- Each user gets a dedicated profile page showcasing all the prompts they've shared and allowing them to edit or delete created prompts
![promptopia-my-page](https://github.com/user-attachments/assets/6c7e0dd5-23eb-4202-81bd-e211e8674123)

### Copy to Clipboard: 
- Easily copy AI prompts to your clipboard for quick use.

## 🎨 Design
Promptopia features a modern and responsive design, utilizing the latest trends in Glassmorphism to enhance the user experience.

## ✅ Extras
- **View Other People's Profiles**: Users can explore the profiles of other creators to view the prompts they've shared. ✅
- ![promptopia-4](https://github.com/user-attachments/assets/3cf06177-364d-4b02-a937-c4003c72ab25)
- **Search Prompts**: Users can search for prompts based on specific tags, usernames or words/phrases on the prompt, making it easier to find prompts related to specific topics ✅
- **Clickable tags**: Allow users to click on the post tag and see all prompts with that tag ✅
![promptopia-5](https://github.com/user-attachments/assets/9a3b9736-1d00-4cd9-8ded-8210d7746213)

## 🔗 Website Link

Visit the live website [here](https://promptopia-od9tlp2qy-paulo-de-melo-borges-projects.vercel.app/).

## 💭 Thoughts
Overall this was a good tutorial and helped me with my first contact with Next.js, especially with file structuring and routing. During the development I encountered several challenges that helped me deepen my understanding of the tecnologies used. For example, one issue was when the message 'Try signing in with a different account' apperead when attempting to log in. After searching for a long time and finding no solution, I reviewed the console logs and Next Auth warnings, and discovered that the `NEXTAUTH_URL`and `NEXTAUTH_SECRET` were not defined, even though they were. So this was resolved by moving the `.env` file from the `utils` directory to the root of the project. Now I plan to deepen my Next.js and React knowledge.
