shitarch-linux

An Arch Linux remix designed specifically to make your life worse.

We benchmarked misery and achieved industry-leading results.

shitarch-linux is a revolutionary, next-generation, enterprise-grade productivity-reduction platform built on Arch Linux, because apparently Arch Linux was not difficult enough already.

Our mission is simple: identify every process a computer can perform automatically and transfer responsibility for it to the user, who is presumably unemployed and has unlimited free time.

Automation is temporary. Manual suffering is forever.

⸻

Features

* UUID-only filenames — document.txt is deprecated. Your essay is now 550e8400-e29b-41d4-a716-446655440000.
* Manual boot orchestration — each boot stage requires user approval. The computer will not start until you confirm that you want the computer to start.
* Verbose commands — ls has been replaced with list-the-contents-of-the-current-directory-and-explain-why-you-need-them.
* Privilege elevation — sudo is gone. Commands now end in -as-a-superuser, because brevity is a privilege.
* Dependency management — every package dependency must be reviewed, approved, signed, printed, scanned, and faxed to the kernel.
* Manual memory management — a graphical interface lets you approve every simulated memory allocation. Actual memory management remains the kernel’s job; we are evil, not incompetent.
* Assembly-first philosophy — shell scripts are considered an admission of defeat.
* Cryptographic authentication — passwords are replaced by a SHA-512-themed challenge-response ceremony. The ceremony adds no security; it adds paperwork.
* Vague error messages — the system knows what went wrong. You don’t deserve to.
* Clipboard governance — every copy-and-paste operation requires a permit.
* Timekeeping by committee — the clock asks the user what time it is.
* KDE configuration decentralisation — every setting is stored in a different directory, including settings that do not exist.

⸻

Example commands

Want to list files?

list-the-contents-of-the-current-directory-and-explain-why-you-need-them

Want to install a package?

request-package-installation \
  --explain-your-intentions \
  --obtain-three-approvals \
  --print-the-dependency-tree \
  --wait-for-the-next-business-day

Want to become root?

whoami-as-a-superuser

Want to shut down?

begin-the-multi-stage-computer-termination-procedure

Expected output:

Stage 1/47: Confirm shutdown.
Stage 2/47: Confirm that you confirmed shutdown.
Stage 3/47: Explain why shutdown is necessary.
Stage 4/47: Your explanation has been rejected.
Stage 5/47: Please restart the shutdown procedure.

⸻

Error messages

Traditional operating systems explain errors. shitarch-linux believes explanations create unrealistic expectations.

Error	Meaning
Something happened.	Something happened.
Operation completed unsuccessfully.	The operation failed.
Unable to continue at this time.	No.
The requested thing is not available.	We misplaced it.
A condition was encountered.	A condition exists.
Please try again later.	We have no idea.
The system has considered your request.	Rejected.
An unexpected expected condition occurred.	We knew this would happen.
Error: error.	Error.
Success: operation failed.	The reporting subsystem has also failed.
The issue may or may not be related.	We are guessing.
Please consult the documentation.	The documentation says to consult the documentation.

Realistic example

$ pacman -S firefox
shitarch-package-manager 0.0.1
Resolving dependencies...
Dependency resolution has encountered a dependency-related condition.
The condition may be caused by:
  - A missing dependency
  - An existing dependency
  - A dependency that has not yet been invented
  - An unrelated event
Installation aborted.
No further information is available.
Please consult the documentation.
Documentation error: documentation unavailable.
Please consult the documentation.

⸻

The filesystem

Files are no longer organised by folders. Instead, the filesystem uses a revolutionary flat architecture.

Every file is stored at the root of the filesystem and identified by a UUID.

Example:

/
├── 0f8fad5b-d9cb-469f-a165-70867728950e
├── 16fd2706-8baf-433b-82eb-8c7fada847da
├── 550e8400-e29b-41d4-a716-446655440000
└── 6ba7b810-9dad-11d1-80b4-00c04fd430c8

File extensions are prohibited because the filesystem should not be expected to understand your intentions.

To open a file, you must first identify it, prove ownership, submit a request, and explain why you did not simply memorise its UUID.

Here at shitarch linux, we believe the user must train their biology to work with such and efficient operating system

Because of this, the UUID of files will randomly shuffle every boot to allow the user to adapt to predicting RNG calculations

RNG will also be used to add the `.probably` ending to random files to further strengthen the users ability to predict RNG calculations

⸻

Package management

The package manager has been redesigned around the principle that installing software should take longer than writing it.

Each package installation requires:

1. A dependency tree inspection.
2. A manual review of every dependency.
3. A signed declaration of intended use.
4. Three approvals from unrelated users.
5. A reboot to apply the approval.
6. A second reboot because the first reboot invalidated the approval.

Example:

Package: firefox
Dependencies: 184
Review dependency 1/184? [y/N]
Review dependency 2/184? [y/N]
Review dependency 3/184? [y/N]
...
Review dependency 184/184? [y/N]
All dependencies reviewed.
Approval expired during review.
Restarting dependency review...

The package manager is technically correct. You did agree to review every dependency.

⸻

Networking

NetworkManager has been replaced by NetworkNegotiator, a tool that negotiates with your network instead of connecting to it.

$ connect-to-wifi
Scanning for networks...
Network found.
Requesting permission to request permission to connect...
Permission denied.
Reason: insufficient permission to request permission.
Would you like to retry? [y/N]

DHCP is disabled by default. Users must manually negotiate an IP address with the router.

DNS resolution requires the user to explain why a domain name deserves to be resolved.

⸻

Desktop environment

KDE Plasma is supported, but the wallpaper is not loaded until the user manually confirms that the desktop should have a background.

Loading desktop...
Panels: loaded
Widgets: loaded
Wallpaper: awaiting authorisation
Window manager: uncertain
Desktop: mostly present

Every configuration setting is stored in a different file. Some settings are stored in files that are generated only after you change the setting.

Changing a setting requires restarting the relevant component, the desktop session, and occasionally the computer’s entire existence.

⸻

Clipboard management

Copying text requires a clipboard permit.

$ copy "hello world"
Clipboard request submitted.
Waiting for approval...
Approval granted.
Clipboard contents have changed.
Warning: clipboard contents are no longer available.
Reason: clipboard retention policy.

The clipboard clears itself after 0.7 seconds to encourage users to type faster.

⸻

Timekeeping

The system clock does not synchronise with network time servers. It asks the user.

Current time is unknown.
Please enter the current time:
> 14:32
Time accepted.
Warning: the supplied time may be inaccurate.
Please enter the current time again.

Leap seconds require a full system reboot and a signed statement from the user confirming that the Earth has rotated unexpectedly.

⸻

Security

shitarch-linux takes security seriously, mostly by making everything inconvenient.

* Password changes require a reboot.
* Logging in requires explaining why you want to log in.
* Failed authentication messages do not reveal whether authentication failed.
* Root access requires a written justification.
* Security updates require manual approval of every changed file.
* The firewall blocks all incoming and outgoing connections, including the connection needed to configure the firewall.

The default security posture is nothing works, therefore nothing can go wrong.

⸻

Performance benchmarks

All results are independently verified by the shitarch-linux Benchmarking Department.

Task	Conventional Linux	shitarch-linux
Boot time	8 seconds	47 minutes
Install Firefox	20 seconds	3 business days
Copy a file	0.01 seconds	14 approval stages
Connect to Wi-Fi	2 seconds	Pending negotiation
Shut down	3 seconds	User confirmation required
Experience joy	Possible	Unsupported

Benchmarks were conducted on a computer that refused to boot during testing.

⸻

Internationalisation

shitarch-linux supports multiple languages, primarily because the developers accidentally pasted characters from several Unicode tables into the source code.

Occasionally, a phoneme is replaced with a vaguely similar symbol from another writing system. A tiny fraction of words may also be replaced with Chinese characters of approximately equivalent meaning.

This feature is called Unicode-based productivity reduction.

Example:

The 系统 is unable to continue.
Please confirm the operation 𐓘gain.

No linguists were consulted.

No linguists will be consulted.

⸻

Frequently asked questions

Is this actually a Linux distribution?

Not yet. It is currently a conceptual parody of Arch Linux and excessive system complexity.

Why not use a normal operating system?

Normal operating systems are designed to save time. This is a design flaw.

Is it suitable for beginners?

Absolutely not. It is also unsuitable for experts, intermediate users, and anyone who has ever wanted their computer to work.

Can I contribute?

Yes. Please submit a pull request, print it, sign it, scan it, and mail it to the maintainers.

Why is it called shitarch-linux?

We considered arch-linux-but-worse, but the domain was taken by reality.

⸻

Design philosophy

Any process that can be automated should be made manual.

Any process that is already manual should be made more complicated.

Any process that cannot be made more complicated should be documented until it becomes impossible to understand.

shitarch-linux: because your computer should be a full-time job.