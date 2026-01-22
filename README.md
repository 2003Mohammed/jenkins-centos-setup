
# Jenkins on CentOS / RHEL (Port 8090)

This repository demonstrates a **complete Jenkins setup** on CentOS/RHEL-based Linux systems.  
It includes installation, port customization, admin setup, plugin installation, and a sample Freestyle job connected to a Git repository.

---

## Highlights

- Jenkins installed using **YUM/RPM** on Red Hat-based distributions
- Default port changed from **8080 → 8090** (access Jenkins at `http://localhost:8090`)
- Admin user creation & secured setup
- Plugin installation for a functional CI/CD environment
- Sample Freestyle job with Git integration and periodic polling
- Screenshots included for easy reference

---

## Repository Structure

```

Jenkins.txt             # Detailed installation & setup guide
screenshots/           # Screenshots showing builds

````

---

## Sample Build

The included Freestyle job demonstrates:

- Polling a Git repository every minute
- Executing shell commands in the workspace
- Outputting build information, workspace location, and Git branch

This gives a **hands-on demonstration** of Jenkins CI/CD capabilities.

---

## Getting Started

1. Clone this repository  
```bash
git clone https://github.com/2003Mohammed/Jenkins-installation.git
````

2. Open **Jenkins.txt** and follow the step-by-step guide.

   * Note: The setup configures Jenkins to run on **port 8090** instead of the default 8080.
   * Access Jenkins UI at: `http://localhost:8090`

---

## Notes

* This setup uses **CentOS/RHEL**. Debian/Ubuntu users can use `apt` instead.
* Screenshots help you visualize each step after the setup of Jenkins and working with the UI.

---

