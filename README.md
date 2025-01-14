# CDP Documentation Chatbot

## Overview

This project is a chatbot designed to assist users with "how-to" questions related to four Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap. The chatbot extracts relevant information from the official documentation of these CDPs to guide users on performing tasks or achieving specific outcomes within each platform.

## Features

- **How-to Guidance**: Provides step-by-step instructions for common tasks in Segment, mParticle, Lytics, and Zeotap.
- **Advanced Configurations**: Offers guidance on advanced configurations and integrations.
- **Conversational Interface**: Handles natural language queries and provides friendly responses.
- **Keyword and Fuzzy Matching**: Uses keyword and fuzzy matching to find relevant documentation.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/cdp-chatbot.git
   cd cdp-chatbot
   ```

2. **Install Dependencies**:
   ```bash
   python -m pip install -r requirements.txt
   ```

3. **Initialize the Chatbot**:
   ```bash
   python -m app.init_chatbot
   ```

4. **Run the Server**:
   ```bash
   uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
   ```

## Usage

- Access the chatbot at [http://localhost:8000](http://localhost:8000).
- Ask questions like:
  - "How do I set up a source in Segment?"
  - "Creating user profiles in mParticle"
  - "Building audience segments in Lytics"
  - "How can I integrate my data with Zeotap?"

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please contact [anuragmishra4515@gmail.com].
