AI Navigator: Your Ultimate AI & Tech Compass
Overview
AI Navigator is a comprehensive web application designed to help users discover and explore a curated collection of powerful AI tools, essential utility apps, and cutting-edge tech platforms. Whether you're looking for content creation AI, productivity enhancers, development tools, or specialized resources for research and business, AI Navigator provides an intuitive interface to find the perfect solution for your needs.

The application features a modern, responsive user interface with light and dark mode support, efficient search capabilities, category-based filtering, and integration with the Gemini API to provide AI-powered insights about each tool.

Features
Extensive Tool Directory: A constantly growing collection of AI tools, productivity apps, development resources, design tools, and more.

Intelligent Search: Quickly find tools by name, description, category, type, or keywords with live suggestions.

Category Filtering: Refine your search results by selecting specific categories like "AI Tools," "Development," "Design & Creativity," "Productivity," and more.

AI-Powered Insights (Gemini API Integration): Ask Gemini questions directly about any listed tool and get instant, AI-generated answers based on its description and details.

Responsive UI/UX: Optimized for seamless viewing and interaction across all devices (desktop, tablet, mobile).

Theme Toggle: Switch between a sleek light mode and a comfortable dark mode.

Clear and Informative Cards: Each tool is presented with its name, a concise description, relevant tags (e.g., "Free," "Freemium," "Paid," "Open-Source"), and a direct link.

Technologies Used
HTML5: Structure of the web application.

Tailwind CSS: For rapid and responsive UI styling.

JavaScript (ES6+): For all dynamic functionality, search logic, filtering, theme toggling, and API interactions.

Google Gemini API: For AI-powered question answering about the tools.

How to Use
Browse: Scroll through the main page to discover various tools.

Search: Use the search bar to find specific tools. Start typing, and you'll see live suggestions. Press Enter or click the "Search" button to filter results.

Filter by Category: Click on the category buttons (e.g., "AI Tools", "Productivity") to narrow down your results to a specific domain.

Ask Gemini: For any tool card, click the "Ask Gemini about this Tool ✨" button. A modal will open where you can type your question about that specific tool. Click "Get Answer" to receive an AI-generated response.

Toggle Theme: Use the moon/sun icon button in the header to switch between light and dark themes.

Installation and Setup (Local Development)
To run this project locally:

Clone the repository:

git clone <repository-url>
cd ai-navigator

Open index.html: Simply open the index.html file in your web browser. There are no complex build steps as it's a pure HTML, CSS, and JavaScript application.

Note: The Gemini API calls in the browser environment typically require the hosting platform to handle API key injection for security. When running locally, the apiKey variable in script.js is intentionally left blank (const apiKey = "";). In a deployed Canvas environment, this key is automatically provided. For local testing with a personal API key, you would typically manage it securely (e.g., via environment variables or a proxy). However, for this setup within the Canvas, no modification is needed.

Contributing
Contributions are welcome! If you have suggestions for new tools, features, or improvements, please feel free to:

Open an issue to discuss your ideas.

Fork the repository and submit a pull request with your changes.

Developed with ❤️ for the future of AI.
