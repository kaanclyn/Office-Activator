# Office Activator

The Office Activator is a simple batch script tool designed to help users activate Microsoft Office 2019 products, such as Microsoft Office Standard 2019 and Microsoft Office Professional Plus 2019, without the need for purchasing an official license. The tool connects to public Key Management Service (KMS) servers to activate the software automatically.

## Key Features

### Supported Products
- **Microsoft Office Standard 2019**  
- **Microsoft Office Professional Plus 2019**

### Automated Activation
- **KMS Server Connectivity**: The script automatically attempts to connect to multiple KMS servers if the first one fails, ensuring that the activation process is completed smoothly.
- **Product Key Injection**: Automatically inputs the required product key for activation without manual intervention.
  
### Multi-Platform Support
- **Office Version Detection**: Detects both 32-bit and 64-bit versions of Office installed in Program Files and Program Files (x86), adjusting accordingly for activation.
  
### Error Handling
- **Retry Mechanism**: If the connection to the first KMS server fails, the script automatically retries with a different server.
- **Fallback Servers**: A set of KMS servers is preconfigured to maximize the chances of successful activation.
  
### Customization
- **Multiple Activation Attempts**: The script tries multiple KMS servers (with different server addresses) to ensure a successful activation.
- **User-Friendly Output**: The script provides clear output and instructions, including error messages and activation status.

### Security & Privacy
- **No Personal Data Collection**: The script operates without collecting personal or sensitive information, focusing solely on activating Office software.
- **Open Source**: The project is fully open source, allowing users to review and modify the script as needed.

### Instructions
- **Simple Setup**: The script requires no installation. Users can simply download and run the batch file to activate their Office software.
- **Activation Feedback**: Provides feedback on whether the activation was successful or not, guiding users on the next steps.

## Technical Details
- **Platform**: Windows Operating System
- **Technology**: Batch scripting using VBScript and command-line tools like `ospp.vbs` and `slmgr.vbs`.
- **Dependencies**: The script uses built-in Windows tools, so no additional software or installation is required.

## Notes
- **Support**: If you encounter issues during activation, you can contact support via the provided contact details for further assistance.
- **Legal Considerations**: Please note that activating software without a valid license may violate Microsoft’s terms of service. Ensure you are in compliance with local laws and software regulations when using the activator.

