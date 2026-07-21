# NSA Student Manual

A practical field manual for Network and Systems Administrator students.

> Learn it. Build it. Test it. Break it safely. Troubleshoot it. Document it.

## Start here

| Path | Purpose |
|---|---|
| [Student Roadmap](docs/STUDENT-ROADMAP.md) | Recommended learning sequence |
| [Lab Standards](docs/LAB-STANDARDS.md) | Rules for safe, repeatable lab work |
| [Technical Documentation](docs/TECHNICAL-DOCUMENTATION.md) | How to document systems professionally |
| [Troubleshooting Method](docs/troubleshooting/TROUBLESHOOTING-METHOD.md) | A repeatable diagnostic workflow |
| [Resource Library](RESOURCES.md) | Official documentation and learning resources |
| [Command Centre](cheatsheets/COMMAND-CENTRE.md) | Frequently used commands |
| [Templates](templates/) | Reusable documentation templates |
| [Labs](labs/) | Guided hands-on practice |

## Core competency map

1. Computer hardware and operating systems
2. TCP/IP, subnetting, switching, routing, VLANs, DNS and DHCP
3. Windows Server, Active Directory and Group Policy
4. Linux server administration
5. Virtualization, storage, backup and recovery
6. Microsoft 365, identity and messaging
7. Cybersecurity, hardening, monitoring and incident response
8. Automation with PowerShell, Bash and Git
9. Troubleshooting and root cause analysis
10. Technical writing, change control and professional communication

## The NSA workflow

```text
Understand requirements
        ↓
Create a design
        ↓
Record assumptions
        ↓
Build in small stages
        ↓
Validate each stage
        ↓
Secure the system
        ↓
Test failure and recovery
        ↓
Document the final state
        ↓
Present evidence
```

## Golden rules

- Never make a production change without understanding scope, impact and rollback.
- Never use a command you cannot explain.
- Never store passwords, tokens, private keys or personal data in Git.
- Take a snapshot or backup before major lab changes.
- Change one variable at a time while troubleshooting.
- Test name resolution before blaming the network.
- Record exact error messages and timestamps.
- Use least privilege.
- Document the final working state, not only the planned state.
- A screenshot is evidence, not a complete explanation.

## Suggested repository use

Students can fork this repository and maintain a personal learning journal:

```text
student-name-nsa-portfolio/
├── README.md
├── labs/
├── diagrams/
├── scripts/
├── troubleshooting/
├── change-records/
└── reflections/
```

## Safety and ethics

Use these materials only on systems and networks you own or are explicitly authorized to administer. Scanning, testing, credential use and configuration changes must remain inside approved lab scope.

## Maintainer

Prepared for NSA students by Victor Chávez.
