# StylePoint Fashion — WhatsApp Order Automation

**An AI-powered WhatsApp customer service and order-processing automation built with n8n.**

## Project Overview

StylePoint Fashion WhatsApp Order Automation helps a fashion business manage customer enquiries and order requests through WhatsApp.

The system uses AI to understand incoming messages, respond to product enquiries, extract order information, identify missing details, and register complete orders in Google Sheets.

It also sends the business owner a WhatsApp notification when a complete order is registered.

## Business Problem&#x20;

Fashion businesses often receive multiple WhatsApp enquiries and orders, making it difficult to:

- Respond to customers promptly.
- Keep track of customer orders.
- Collect all required order information.
- Reduce repetitive administrative tasks.
- Notify the business owner when new orders arrive.

This automation provides a structured solution to these challenges.

## How the Automation Works

1. **WhatsApp Message Reception:** Receives incoming customer messages through WhatsApp Business Cloud API.
2. **Message Classification:** AI classifies messages as enquiries, orders, or other messages.
3. **AI Customer Support:** Responds to product enquiries using the available product information.
4. **Order Information Extraction:** Extracts customer name, product, size, quantity, and delivery address.
5. **Missing Information Handling:** Requests any required details that are missing.
6. **Order Calculation:** Calculates the order total using the configured product price.
7. **Duplicate Protection:** Checks the incoming WhatsApp message ID against existing records before registering an order.
8. **Order Registration:** Saves complete order details in Google Sheets.
9. **Owner Notification:** Sends the business owner a WhatsApp notification containing the order details.

## Technologies Used

- **n8n:** Workflow automation and orchestration.
- **WhatsApp Business Cloud API:** Customer messaging and notifications.
- **Anthropic AI:** Message understanding and structured order extraction.
- **Google Sheets:** Order registration and record management.
- **AI-powered classification:** Separates enquiries, orders, and other messages.

## Key Features

- Automated WhatsApp customer support.
- AI-powered message classification.
- Structured order information extraction.
- Missing-information detection.
- Automatic order-total calculation.
- Duplicate-message detection.
- Google Sheets order management.
- WhatsApp owner notifications.

## Business Value

This solution helps a fashion business:

- Reduce repetitive customer-service tasks.
- Organise incoming orders.
- Improve response consistency.
- Reduce manual order-entry work.
- Improve visibility into incoming orders.
- Spend more time on sales and business operations.

## Security and Testing

- API credentials are stored in n8n credentials rather than hardcoded into workflow logic.
- Test mode is enabled during development.
- Orders are assigned a **Pending confirmation** status.
- The workflow is not intended for live customer operations until production configuration, testing, and security review are completed.
- Workflow exports must be checked for sensitive information before publication.

## Project Status

**Development and testing completed for the core workflow.**

The workflow has been tested using a WhatsApp test recipient, including customer enquiries, order extraction, missing-information handling, Google Sheets registration, owner notifications, and duplicate-message lookup.

The automation remains inactive and in test mode pending final security review and production deployment.

## Skills Demonstrated

- Workflow automation with n8n.
- AI integration and prompt engineering.
- WhatsApp Business Cloud API integration.
- Structured data extraction.
- Conditional logic and workflow routing.
- Google Sheets integration.
- Duplicate-message handling.
- Business process automation.

## Future Improvements

- Product catalogue integration.
- Inventory and stock availability checks.
- Multi-message order completion.
- Customer order-status tracking.
- Production deployment and monitoring.


