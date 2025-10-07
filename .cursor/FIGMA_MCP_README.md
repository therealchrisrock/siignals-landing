# Figma MCP Server Configuration

## Personal Access Token Setup

1. Generate a Figma Personal Access Token:
   - Go to Figma Account Settings
   - Navigate to "Personal Access Tokens" section
   - Create a new token with appropriate permissions

2. Configure the token:
   - Set the FIGMA_ACCESS_TOKEN environment variable
   - Option 1 (Recommended): In your shell
     ```bash
     export FIGMA_ACCESS_TOKEN=your_token_here
     ```
   - Option 2: In your project's .env file
     ```
     FIGMA_ACCESS_TOKEN=your_token_here
     ```

## Troubleshooting
- Ensure the token has the correct scopes
- Verify network connectivity to Figma API
- Check that the token is not expired

## Security
- Never commit your access token to version control
- Rotate tokens periodically
- Use environment variables or secure secret management
