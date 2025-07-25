🚀 Launch the Project Without Taking the Course
Want to skip the tutorial and launch your own version of the Fizzi website on Prismic right away? Follow these quick steps:

✅ 1. Clone the Project with the Starter Template
Use the official Slice Machine starter to scaffold your project:

bash
Copy
Edit
npx @slicemachine/init@latest --starter course-fizzi-next
🌐 2. Configure Your Prismic Repository
Open the Prismic dashboard.

Select the content language: English - United States.

🧩 3. Set Up the Demo Content Automatically
Run the content setup script to populate your Prismic repository:

bash
Copy
Edit
npm run set-up-content
📦 4. Publish the Prebuilt Content Release
Follow the instructions in your terminal.

Click the generated URL to open the release in Prismic.

Review and publish the content directly.

🔧 5. Configure the Slice Simulator
Ensure the Slice Simulator is properly set up for local development by assigning the simulator URL:

txt
Copy
Edit
http://localhost:3000/slice-simulator
This allows you to preview and build custom Prismic slices visually in your development environment.
