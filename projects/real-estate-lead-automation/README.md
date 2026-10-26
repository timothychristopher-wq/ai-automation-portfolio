# Real Estate Lead Capture & Qualification Automation

## Project Overview

This project demonstrates how workflow automation can help real estate businesses manage customer enquiries, send email notifications, and classify potential customers according to their property budgets.

**Built with:** n8n, Google Forms, Google Sheets, and Gmail

**Project type:** Business workflow automation

**Status:** Built and tested

## The Business Problem

Real estate agencies receive enquiries from potential buyers and renters. Manually recording each enquiry, notifying agents, and responding to customers can create unnecessary work and make follow-up harder to manage.

## The Solution

I built an n8n workflow that connects Google Forms, Google Sheets, and Gmail to automate the initial lead-handling process.

### How It Works

1. A potential customer submits a real estate enquiry through Google Forms.
2. The enquiry is recorded in Google Sheets.
3. n8n detects the new lead.
4. The workflow sends an email notification to the business owner.
5. The customer receives an automated acknowledgement email.
6. The workflow classifies the lead according to the submitted budget.
7. A Merge node brings the priority branches back together so processing can continue.

## Lead Qualification Rules

| Priority | Budget |
|---|---|
| High | ₦50,000,000 and above |
| Medium | ₦20,000,000 to below ₦50,000,000 |
| Low | Below ₦20,000,000 |

These thresholds are configurable to match a real estate business's target market.

## Tools and Technologies

- **n8n:** Workflow orchestration and automation logic
- **Google Forms:** Customer enquiry collection
- **Google Sheets:** Lead data storage
- **Gmail:** Automated email notifications and customer acknowledgements
- **IF nodes:** Budget-based lead qualification
- **Merge node:** Recombining the priority branches

## Business Value

This workflow demonstrates how a real estate business can:

- Reduce repetitive manual data entry.
- Receive prompt notifications about new enquiries.
- Acknowledge customer enquiries automatically.
- Organize leads using consistent budget categories.
- Establish a foundation for a more structured follow-up process.

Actual time savings and business results would need to be measured in a live business environment.

## Potential Improvements

Future versions could include:

- Automatic follow-up reminders.
- Lead status tracking in Google Sheets.
- Integration with a CRM system.
- AI-assisted enquiry categorization.
- Reporting on lead sources and conversion rates.

## Interested in Workflow Automation?

I am available to discuss practical automation solutions for real estate agencies, small businesses, and service providers.

**GitHub portfolio:** https://github.com/timothychristopher-wq

**Contact:** timothyasuelimen303@gmail.com

*This project is a demonstration of business workflow automation using connected applications and conditional logic.*
