# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

I chose Azure App Service (PaaS) over a Virtual Machine (IaaS) because it abstracts away server maintenance, OS patching, and networking configuration. It allows for seamless deployment directly from GitHub and native integration with Azure Environment Variables, making it more secure and efficient for hosting a Flask application than manually configuring a web server on a VM.

### Assess app changes that would change your decision.

I would switch to a VM if the application required full OS-level control, custom networking appliances, nonstandard runtimes, or tightly coupled background services that are difficult to run within App Service constraints. A VM could also make sense if we needed specialized system dependencies, custom reverse proxy behavior, or enterprise controls that must be configured at the host level.
