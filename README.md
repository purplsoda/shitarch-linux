shitarch-linux

a arch linux remix designed specifically to make your life worse (we have benchmarked misery and achieved industry leading results)

shitarch-linux is a revolutionary next generation enterprise grade productivity reduction platform built on arch linux because apparently arch linux was not difficult enough already

our mission is simple: identify every single process that a computer can perform automatically and transfer responsibility for that process to the user, who is presumably unemployed and has unlimited time

the user can create their own automations but we will somehow make it so its only possible if the automation is written in asm because using python to rename a file is apparently a threat to national security

we have taken the KISS principle and improved it by removing the simplicity entirely

we call this 逆向 productivity

stupid functions (industry leading improvements)

1. filesystem naming improvements

human readable filenames are a legacy technology developed by people who believed computers should be understandable

we have eliminated this limitation

every file and directory is identified exclusively by a UUID

$ list-files-and-directories-in-selected-directory
a7f93d2c-84b1-4e6f-9a2d-73c8e41b5f06
c1b72a90-5d3e-48f1-b604-9a7c2e83d145
8e3f0b71-2a94-46cd-b815-5d7a9c20e634

which one is your homework?

you will remember

you must remember

the filesystem remembers nothing about your emotional attachment to homework-final-FINAL-v7-reallyfinal.txt

that file is dead

it has been reborn as d4a1c9e2-7f63-4b80-a251-9e6d3c7f1048

the user is encouraged to memorise every UUID using traditional biological storage methods

if you forget a UUID, you may search for it manually by opening every directory recursively and inspecting every file individually

this process has been optimised by removing the search function

we call this cognitive offloading reversal

2. super efficient boot

we have decided the arch linux boot process is too slow so instead the user will dictate the boot speed by manually executing every process

every boot stage must be executed in the correct order and in time

BOOT SEQUENCE INITIALISED
00:00.000  LOCATE FIRMWARE
00:00.250  IDENTIFY BOOTLOADER
00:00.500  LOAD KERNEL
00:00.750  INITIALISE INITRAMFS
00:01.000  MOUNT ROOT FILESYSTEM
00:01.250  START SYSTEMD
PRESS ENTER ON BEAT
TOO EARLY
TOO LATE
UNKNOWN

the computer now functions like a rhythm game designed by someone who considers 60 BPM to be an advanced mathematical concept

miss one deadline and the sequence restarts

execute one stage out of order and the sequence restarts

successfully complete every stage and the system informs you that the deadline was missed

we call this deterministic suffering scheduling

the actual kernel still handles real boot operations internally because we have limits (they are somewhere between our moral standards and our available development time)

3. command naming improvements

unix commands are too short

ls contains two characters

two

we have therefore replaced it with the following enterprise-grade interface

list-files-and-directories-in-selected-directory

want to list files recursively?

list-files-and-directories-in-selected-directory-in-a-recursive-manner

want hidden files?

list-files-and-directories-in-selected-directory-including-hidden-files

want both?

list-files-and-directories-in-selected-directory-including-hidden-files-in-a-recursive-manner

want detailed output?

list-files-and-directories-in-selected-directory-including-hidden-files-in-a-recursive-manner-while-displaying-file-permissions-ownership-size-and-other-information-that-will-be-used-by-absolutely-nobody

we have replaced command flags with complete English descriptions because apparently -r was an unacceptable compression ratio

the command parser requires every word to be spelled correctly

a typo in character 193 causes the entire command to fail

COMMAND REJECTED
Your command was 246 characters long.
Expected: 247 characters.
We are sorry for the inconvenience.
Error code: 1

we call this verbose interface optimisation

4. privilege escalation improvements

sudo is far too short

it is also too easy to type without thinking about the consequences

we have replaced it with suffix-based privilege declaration

instead of

sudo pacman -Syu

the user must execute

update-the-entire-operating-system-and-all-installed-packages-as-a-superuser

every privileged operation must end with -as-a-superuser

forget the suffix and the command fails

type the suffix incorrectly and the command asks whether you intended to perform the operation as a non-privileged user

answer yes and the operation fails

answer no and the operation fails

we call this privilege awareness through repeated disappointment

5. password security improvements

passwords are insecure because people can remember them

shitarch-linux has therefore introduced SHA-512 credential entry

AUTHENTICATION REQUIRED
Please enter the 128-character hexadecimal SHA-512 digest
of your password.
> ________________________________________________
AUTHENTICATION FAILED
Reason: the provided credential was not sufficiently credential-like.

the system uses a challenge-response protocol so that a captured hash cannot simply be replayed as a password

the challenge-response client must be written in assembly before the user can log in

we call this cryptographic inconvenience as a service

security researchers have described the interface as unnecessarily complicated

we have interpreted this as a positive security audit

6. manual memory management

automatic memory management hides the physical reality of RAM

we have therefore introduced a human-in-the-memory-loop interface

every application must submit a formal request for memory allocation

MEMORY ALLOCATION REQUEST 000001
Application: Dolphin
Requested memory: 384 MiB
Available memory: 7,421 MiB
Please identify the physical pages to allocate.
Selected pages: 0
Required pages: 98,304
Would you like to continue?
[Y] yes
[N] no
[M] manually inspect every page

selecting M opens a list of physical pages

the list contains approximately eight million entries on a sufficiently large machine

we believe that the user should understand exactly what the computer is doing before opening a file manager

the kernel still manages physical memory internally because manually handling real page tables from a desktop application would be a security and stability disaster

we are evil, not responsible for kernel-level memory corruption

7. package management improvements

pacman is too efficient

dependency resolution is now a human resources department

PACKAGE INSTALLATION REQUEST
Package: firefox
Direct dependencies: 87
Transitive dependencies: 642
Dependency review required.
Approve dependency 1 of 729?
[Y] approve
[N] reject
[W] why does this exist

selecting W opens the documentation

the documentation requires another package

that package requires another package

the user is now reviewing the dependency tree of the documentation required to understand the dependency tree

we call this recursive dependency enlightenment

if the installation succeeds, the system displays:

TRANSACTION COMPLETED
The requested package has been installed.
However, one dependency was not reviewed.
Please reinstall the package to continue.

8. vague error message improvements

traditional error messages explain what happened

we have removed this unnecessary information

all error messages are now generated by our proprietary ambiguity engine

ERROR 1
Something happened.
ERROR 2
Something else happened.
ERROR 3
The previous thing may have caused the current thing.
ERROR 4
Operation unsuccessful.
Please ensure that the operation is operating correctly.
ERROR 5
Unexpected expected behaviour detected.
ERROR 6
The system could not determine whether the system was able to determine the requested determination.
ERROR 7
Success.
Unfortunately, the operation failed.
ERROR 8
An error occurred while attempting to report an error.
The original error may or may not have occurred.
ERROR 9
Error resolving error.
The error resolver returned an error while resolving the error that occurred during error resolution.
Please resolve the error.
ERROR 10
The operation completed with status: maybe.

our flagship error is:

FATAL ERROR
Something has gone wrong.
We know what it is.
We cannot tell you.
Have a nice day.

we call this context-free diagnostic transparency

9. networking improvements

DHCP is an unacceptable loss of user autonomy

the user must manually configure the IP address, subnet mask, default gateway, DNS resolver, routing table, interface parameters and every other setting that might conceivably be required for networking

NETWORK CONFIGURATION
IP address: required
Subnet mask: required
Gateway: required
DNS resolver: required
Network status: not available
Reason: network configuration incomplete
To configure the network, please access the network configuration utility.
The network configuration utility requires an active network connection.

we call this offline-first networking

the internet is available only after the user has successfully completed the configuration process

we have therefore ensured that nobody can access the documentation required to configure the internet

10. graphical interface improvements

KDE Plasma is too convenient

we have therefore introduced several enterprise-grade enhancements

* the desktop wallpaper is stored under a UUID
* the login screen uses a separate theme configuration system
* the lock screen uses a different configuration system
* changing the wallpaper requires restarting the appropriate service
* restarting the appropriate service requires consulting the documentation
* the documentation requires opening a browser
* the browser requires a working desktop environment

we call this cross-component integration through intentional fragmentation

the login screen and lock screen are now guaranteed to look completely different

consistency is a form of complacency

11. clipboard improvements

copying and pasting is too easy

we have replaced the clipboard with a manually managed text transfer interface

copying text requires the user to acknowledge the transfer

pasting text requires the user to acknowledge the receipt

CLIPBOARD TRANSFER REQUEST
Source: Application A
Destination: Application B
Transfer payload: 14 characters
Do you authorise the transfer of this payload?
[Y] yes
[N] no

if the transfer contains Unicode characters, the user must acknowledge the encoding

if the transfer contains emoji, the user must acknowledge that the characters may occupy multiple bytes

if the transfer contains a newline, the user must acknowledge the existence of line endings

we call this data sovereignty

12. update management improvements

automatic updates are a threat to user engagement

every update must be manually approved

UPDATE AVAILABLE
Packages to upgrade: 1,284
Review package 1/1284?

after reviewing every package, the user must approve the review

after approving the review, the user must confirm the approval

after confirming the approval, the user must confirm that the confirmation was intentional

after confirming that the confirmation was intentional, the system asks whether the user would like to postpone the update

selecting yes postpones the update

selecting no asks whether the user is sure

we call this change management maturity

13. timekeeping improvements

system clocks are too automatic

the user must periodically confirm the current time

TIME SYNCHRONISATION REQUEST
System time: unknown
Actual time: unknown
Enter the correct time:
> __:__:__
Thank you.
The supplied time differs from the system time.
Please correct the system time.

NTP remains available but requires manual approval for every synchronisation attempt

we call this temporal accountability

14. documentation improvements

man pages are too informative

every manual references another manual

$ man shitarch
SEE ALSO:
shitarch-config(7)
$ man shitarch-config
SEE ALSO:
shitarch(1)

the user is encouraged to explore the documentation indefinitely

the loop is not a bug

the loop is an educational journey

we call this circular knowledge management

15. shell improvements

command completion is disabled

aliases are disabled

history is disabled

the prompt does not display the current directory

the prompt does not display the username

the prompt does not display the hostname

the prompt does not display whether the last command succeeded

we call this minimalist situational awareness

the terminal prompt is now:

>

this represents the user’s relationship with the operating system

16. printer improvements

printers are already difficult to use

we have decided to improve the process by requiring users to configure the print queue manually

before printing a document, the user must confirm:

* the printer exists
* the printer is connected
* the printer has paper
* the printer has ink
* the printer understands the document
* the document understands the printer
* the printer has acknowledged the existence of the document

PRINT REQUEST FAILED
Reason: printer communication unsuccessful.
Printer status: available.
Document status: available.
Communication status: unavailable.
Please ensure that all components are communicating correctly.

we call this physical document orchestration

17. file deletion improvements

deleting files is too easy

the user must submit a deletion request containing the target UUID, inode number, file size and a written justification

DELETION REQUEST
Target: 8e3f0b71-2a94-46cd-b815-5d7a9c20e634
Reason for deletion: required
Are you certain? [Y/N]
Are you certain that you are certain? [Y/N]
Would you like to reconsider your certainty? [Y/N]

the file is then moved into a recycle directory

the recycle directory has a UUID

the UUID is not displayed

we call this reversible deletion management

18. user account improvements

creating a user account requires the user to create another user account

the second account is responsible for authorising the first account

the first account must then authorise the second account

the two accounts cannot log in until they have both been authorised

we call this distributed identity verification

19. shutdown improvements

shutting down the computer is too simple

the user must first request permission to terminate the current session

SHUTDOWN REQUEST
Active processes: 47
Terminate all active processes?
[Y] yes
[N] no

selecting yes opens a second confirmation

selecting no returns to the desktop

selecting yes again asks whether the user would like to save their work

selecting yes opens a file manager

the file manager requires a functioning desktop environment

we call this graceful termination governance

performance benchmarks

we conducted a completely objective benchmark using a stopwatch, a spreadsheet and an individual who was not permitted to leave the room

Operation	Normal Arch	shitarch-linux
Open file manager	0.4 seconds	14 minutes
List files	0.01 seconds	23 seconds
Install package	15 seconds	2 hours
Change wallpaper	3 seconds	47 minutes
Configure networking	30 seconds	3 business days
Delete a file	1 second	12 confirmation dialogs
Read an error message	2 seconds	Still investigating
Boot desktop	8 seconds	Deadline exceeded
Regret installation	Immediate	Before installation

the results demonstrate a 400% improvement in user engagement

we cannot disclose the methodology because the benchmark script is written in assembly and its author has forgotten the UUID of the source file

known issues

* users report that the operating system is inconvenient
* users report that commands are too long
* users report that error messages contain insufficient information
* users report that they cannot find their files
* users report that the system requires too much manual configuration
* users report that updates take too long
* users report that the computer is technically functional but spiritually hostile

all issues have been classified as expected behaviour

users who report these issues will be automatically enrolled in our advanced inconvenience programme

design philosophy

1. if something can be automated make it manual
2. if something can be simplified make it complicated
3. if something works perfectly do not touch it because it is probably the only thing keeping the system operational
4. if the user complains, rebrand the complaint as a feature
5. if a feature is too difficult to explain, call it enterprise grade
6. if a command is too long, add more words
7. if an error is too vague, remove another noun
8. if the system is broken, inform the user that the system is operating within expected parameters

we call this continuous inconvenience delivery

final statement

shitarch-linux is not an operating system

it is a prolonged negotiation between a human being and a machine that has decided to become a middle manager

we have successfully transformed a computer from a tool into a full-time administrative responsibility

the rock remains faster to boot

the rock does not require dependencies

the rock does not need a desktop environment

the rock does not ask you to confirm that you confirmed the confirmation

the rock is also not compatible with KDE Plasma

we are working on it

(estimated completion date: unknown)

(estimated reason: something happened)

shitarch-linux — making computers worse, one unnecessary abstraction at a time.