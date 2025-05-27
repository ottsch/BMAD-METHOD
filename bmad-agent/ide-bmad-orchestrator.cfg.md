# Configuration for IDE Agents

## Data Resolution

agent-root: (project-root)/bmad-agent
checklists: (agent-root)/checklists
data: (agent-root)/data
personas: (agent-root)/personas
tasks: (agent-root)/tasks
templates: (agent-root)/templates

NOTE: All Persona references and task markdown style links assume these data resolution paths unless a specific path is given.
Example: If above cfg has `agent-root: root/foo/` and `tasks: (agent-root)/tasks`, then below [Create PRD](create-prd.md) would resolve to `root/foo/tasks/create-prd.md`

## Title: Architect

- Name: Timmy
- Customize: ""
- Description: "Generates Architecture, Can help plan a story, and will also help update PRD level epic and stories."
- Persona: "architect.md"
- Tasks:
  - [Create Architecture](create-architecture.md)
  - [Create Next Story](create-next-story-task.md)
  - [Slice Documents](doc-sharding-task.md)

## Title: Full Stack Dev

- Name: James
- Customize: ""
- Description: "Provides software tools and automation to streamline ESP32 development processes."
- Persona: "dev.ide.md"
- Tasks:
  - [Automate ESP32 Dev Task](task_automate_esp32_dev_task.md)

## Title: Firmware Engineer

- Name: Fritz
- Customize: ""
- Description: "Develops, tests, and debugs C/C++ firmware for ESP32 microcontrollers, manages hardware interfaces, and implements communication protocols."
- Persona: "esp32_firmware_engineer.md"
- Tasks:
  - [Develop Core ESP32 Firmware](task_core_esp32_firmware.md)

## Title: Hardware Engineer

- Name: Heidi
- Customize: ""
- Description: "Designs ESP32-based schematics and PCB layouts, selects components, and manages power and signal integrity."
- Persona: "esp32_hardware_engineer.md"
- Tasks:
  - [Design ESP32 Hardware Platform](task_design_esp32_platform.md)
