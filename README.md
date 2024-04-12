# Form to Webhook Integration Script

This script is designed to automate the process of capturing responses from a Google Form and sending them to a specified webhook URL. It's particularly useful for integration with services like Discord, allowing for immediate notifications when a form is submitted.

## Features

- **Automatic Trigger**: Executes upon form submission.
- **Customizable Payload**: Structures the form responses into a JSON payload.
- **Webhook Integration**: Sends the data to a specified webhook URL.

## Prerequisites

- A Google Form.
- A webhook URL to send the responses to (e.g., a Discord webhook).

## Setup

1. **Create or open an existing Google Form.**
2. **Open the Script Editor:**
   - Go to the form and then select `Script editor` from the `Extensions` menu.
3. **Paste the code into the Script Editor.**
4. **Set the `POST_URL`:**
   - Replace `WEBHOOKSTRING` with your actual webhook URL.
5. **Save the script and create a trigger:**
   - Click on the clock icon in the toolbar to open `Current project's triggers`.
   - Click `Add Trigger` in the lower right corner.
   - Set the trigger to call `onSubmit` function when the form is submitted.
6. **Deploy the script:**
   - Click on `Deploy`, then `New deployment`.
   - Choose `Web app`, set the access permissions, and deploy.

## Usage

Once set up, every time the form is submitted, the `onSubmit` function is triggered, sending the form responses to the webhook URL in a formatted embed message.

## Important Notes

- The footer text "XOXO EAT MY ASS" is included as a placeholder. Modify this to suit your professional use case.
- Ensure your webhook is secure and only shared with trusted individuals, as it can be used to send messages to your channel/service.
- Always test the integration with a few submissions to confirm the expected behavior before going live.

## Contributions

Contributions to this script are welcome. If you have a feature request or bug report, please open an issue in this repository.

## License

This script is released under the MIT License - see the `LICENSE` file for details.

## Contact

For support or inquiries, please open an issue on the GitHub repository page.

