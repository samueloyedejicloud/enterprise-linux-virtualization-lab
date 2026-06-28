---

# Troubleshooting

During the initial deployment attempt, the virtual machine did not boot successfully. After starting the virtual machine, the screen remained black with a blinking cursor for more than 30 minutes without displaying the Ubuntu installation interface.

## Issue Encountered

- Virtual machine displayed a black screen with a blinking cursor.
- Ubuntu installer failed to load.

## Investigation

To identify the cause, I reviewed the virtual machine configuration, compared my setup with official documentation and community resources, and verified the hardware allocation.

The compute resources assigned to the virtual machine were sufficient:

- 4 GB RAM
- 4 vCPUs
- 40 GB Virtual Disk

After reviewing the configuration, I determined that the Ubuntu ISO had not been properly configured as the initial boot media during the first deployment attempt.

## Resolution

To resolve the issue, I:

1. Removed the original virtual machine.
2. Created a new virtual machine.
3. Attached the Ubuntu ISO correctly during the setup process.
4. Started the virtual machine again.
5. Successfully completed the Ubuntu installation.

## Outcome

The operating system booted successfully, confirming that the issue was related to the virtual machine configuration rather than the host hardware or allocated resources.

