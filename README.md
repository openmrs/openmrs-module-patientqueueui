# Patient Queue UI Module

The **Patient Queue UI Module** is a user interface extension for the [Patient Queueing Module](https://github.com/openmrs/openmrs-module-patientqueueing). It provides an App Framework-based frontend to allow healthcare providers and staff to manage patient queues efficiently within an OpenMRS-based health system.

This module is intended to work alongside the backend Patient Queueing API and offers a visual dashboard, messaging features, and queue management capabilities tailored for clinical workflows.

---

## 🌟 Features

- **Queue Management Dashboard**  
  Visual interface for listing and managing patients in the queue.

- **Provider View**  
  Enables care providers to:
    - View patients queued to them or in their location.
    - Pick and complete patients from the queue.

- **Messaging System**
    - Send and receive messages related to patient care among providers.
    - Improve collaboration and continuity of care.

- **Patient Triage Interface**  
  Supports prioritization, visit tracking, and comments related to patient conditions.

---

## 📦 Requirements

- OpenMRS Core 2.x
- [Patient Queueing Module](https://github.com/openmrs/openmrs-module-patientqueueing) (must be installed and running)

---

## ⚙️ Installation

1. **Clone or download this repository**
   ```bash
   git clone https://github.com/openmrs/openmrs-module-patientqueueui.git
2. **Build the module**
   mvn clean install

3. ## 📦 Deploy the Module

1. Locate the `.omod` file in the `omod/target/` directory after build.
2. Copy it into the `modules/` directory of your OpenMRS application.
3. Restart OpenMRS to load the module.

---

## 🚀 Usage

After installation and deployment:

- Log in to the OpenMRS Reference Application.
- Navigate to the **Patient Queue Dashboard** via the home screen or app menu.
- Use the dashboard to:
    - View all patients currently in queue.
    - Assign providers to patients.
    - Pick and complete queued visits.
    - Send and receive messages among providers.

---

## 🔧 Configuration

You can customize the UI by:

- Extending the App Framework configuration to support custom workflows.
- Integrating additional HTML forms for triage or vitals.
- Setting user roles and privileges to control queue access and messaging.

> 🔐 **Ensure appropriate permissions** are set for users to access queue management and messaging features.

---

## 📜 License

This module is distributed under the [OpenMRS Public License](https://openmrs.org/license/).

---

## 🤝 Contributing

We welcome contributions from the OpenMRS community and beyond!

To contribute:

1. **Fork** the repository.
2. **Create** a new feature branch.
3. **Commit** your changes.
4. **Submit** a pull request (PR).

> For major changes, consider opening an issue to discuss the proposal before starting work.

---

## 👥 Maintainers

This module is maintained by the OpenMRS community.

For questions, bug reports, or feature requests, please use the [GitHub Issues page](https://github.com/openmrs/openmrs-module-patientqueueui/issues).

---

## 🔗 Related Modules
[Patient Queueing Module (API)] (https://github.com/openmrs/openmrs-module-patientqueueing).
