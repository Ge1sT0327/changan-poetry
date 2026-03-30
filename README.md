Poetry of Chang'an: AI-Powered Ancient Chinese Poetry Generator
License: MITCore Technology: HTML5/CSS3/JavaScriptAI API: GLM-4.6V-FlashX
A visually stunning, interactive web application that generates classical Chinese poetry (Shi and Ci) inspired by the cultural heritage of Chang'an (ancient Xi'an). Blending traditional Tang Dynasty aesthetics with modern AI technology, this project creates personalized poetry based on user-specified themes, poetic forms, and stylistic preferences.
Key Features
Core Functionality
AI-Powered Poetry Generation: Creates authentic classical Chinese poetry (7-character jueju, 5-character jueju, 7-character lüshi, and Ci poetry forms like Shui Diao Ge Tou/Xi Jiang Yue)
Stylistic Customization: Choose from 5 distinct poetic styles (Heroic, Graceful, Desolate, Zen-like, Homesick)
Thematic Personalization: Integrate user-provided keywords (Chang'an cultural symbols like Giant Wild Goose Pagoda)
Poetry Analysis: Modern Chinese interpretation and appreciation of generated works
History Tracking: Local storage of generated poems for later retrieval
Poster Export: High-quality image export of poetry display (via html2canvas)
Aesthetic & Interactive Design
Traditional Chinese Visuals: Vertical text layout (vertical-rl writing mode) with authentic KaiTi font
Cultural Color Palette: Cinnabar red, black, silk white, and gold accents inspired by Tang Dynasty art
Background Ambiance: Customizable background imagery with semi-transparent overlay
Interactive Music Control: Traditional Chinese instrumental background music with visual feedback
Typewriter Animation: Elegant character-by-character text reveal effect
Responsive Design: Adapts to different screen sizes while maintaining cultural aesthetic
Technical Stack
Frontend
HTML5: Semantic structure with traditional Chinese typography support
CSS3: Custom properties (variables), animations, transforms, and backdrop filters
JavaScript (Vanilla):
Asynchronous API calls
LocalStorage for history persistence
DOM manipulation and animations
Audio playback control
Canvas-based screenshot/export functionality
External Dependencies
html2canvas: For poster/image export
GLM-4.6V-FlashX API (Zhipu AI): For AI poetry generation
Traditional Chinese instrumental music (Guzheng): For ambient audio
Deployment & Setup
Prerequisites
A modern web browser (Chrome, Firefox, Safari, Edge)
API key for Zhipu AI GLM-4.6V-FlashX (replace in the code)
Web server (local or remote - GitHub Pages, Netlify, Vercel, etc.)
Local Setup
Clone the repository:git clone https://github.com/your-username/changan-poetry-generator.gitcd changan-poetry-generator
Replace API credentials:Open index_with_music.htmlUpdate TEXT_API_KEY with your Zhipu AI API keyVerify the TEXT_API_URL and TEXT_MODEL values
Customize media assets (optional):Replace 1.jpg with your preferred background imageUpdate 崔江卉 - 清平乐 古筝.mp3 with your preferred background music
Launch the application:Open index_with_music.html in a modern web browserOr use a local web server (e.g., Python's http.server):python -m http.server 8000Access at http://localhost:8000
GitHub Pages Deployment
Fork the repository to your GitHub account
Update the API key and media assets as needed
Enable GitHub Pages in repository settings (Settings → Pages → Source: main branch)
Access via https://your-username.github.io/changan-poetry-generator/
Usage Guide
Input Customization:Select poetic form (genre) from the first dropdownChoose stylistic preference from the second dropdownEnter a keyword (Chang'an cultural symbol) in the input field
Generate Poetry:Click "智咏长安" (Compose Chang'an Poetry) buttonWatch the typewriter animation as the poem is revealed
Additional Actions:诗意解签 (Poetry Analysis): View modern interpretation of the poem生成海报 (Export Poster): Download high-quality image of the poetry display游侠留墨 (History): Access previously generated poemsMusic Control: Toggle traditional Chinese instrumental background music (top-right button)
Design Details
Color Palette--zhu-sha (#c21f30): Cinnabar red (traditional Chinese auspicious color)--xuan-se (#1a1a1a): Black (symbol of depth and solemnity)--juan-bai (#f9f6f0): Silk white (paper/text color)--jin-se (#d4af37): Gold (accent/decoration color)--an-jin (#8c7322): Dark gold (secondary accent)
Typography
KaiTi/STKaiti font (traditional Chinese calligraphy font)
Vertical text layout (mimicking traditional Chinese writing)
Character spacing optimized for classical poetry reading
Animations
Rotating music control button (when playing)
Blinking cursor during text generation
Hover effects with cultural color transitions
Smooth drawer animation for history panel
Notes & Limitations
API Requirements: Requires valid Zhipu AI API key (rate limits and costs may apply)
Browser Compatibility: Best viewed in modern browsers (supports CSS backdrop-filter and ES6+)
Audio Playback: Browser autoplay policies require user interaction for audio playback
Local Storage: History data is stored in browser localStorage (cleared when browsing data is deleted)
Background Assets: Local file paths for images/audio need proper hosting for remote deployment
License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments
Zhipu AI for GLM-4.6V-FlashX API
html2canvas library for screenshot functionality
Traditional Chinese music composers and performers
The cultural heritage of Chang'an (Xi'an) and Tang Dynasty poetry
"When words fail, poetry speaks" - Inspired by the poetic legacy of Chang'an, the eternal capital of Tang Dynasty China.
