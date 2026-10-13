# Foxclone - A Bootable Clone or Image

## At a Glance

Foxclone is a live environment for copying a disk when Windows is not running on it. Clone mode writes one disk onto another. Image mode writes a file. Both can destroy the wrong device if you swap the ends. The program shows model and size so you can match them to the stickers or to what you know about the machine. Use those, not the order the disks appeared.

- Boot from the Foxclone USB, not from the disk you are saving
- Source and target identified by size
- Images named with the PC and the date
- A target disk you can afford to erase
- Time enough to finish before you unplug

1. Boot the USB.
2. Note which disk is the system by size.
3. Choose backup or clone and set the other disk as the destination.
4. Start and wait for completion.
5. Restore only when you have again read the target.

[![Open Foxclone](https://img.shields.io/badge/Open-Foxclone-166534?style=for-the-badge&logo=linux&logoColor=white)](https://bringer1992cromer.github.io/.github/foxclone-disk-image)

## Fits

A full copy before a disk swap or a risky install. A poor fit for a handful of files. A poor fit for a failing disk that should be file-copied first. A poor fit if you are unsure which disk is which. Stop and label them.

## Requirements

| Item | Expectation |
|---|---|
| USB | A Foxclone boot stick |
| Second disk | Big enough for the copy |
| PC | USB boot works |

## Fixes

The wrong disk was listed first. Sort by size, not by order.
The image disk is full. The destination was too small.
Clone finished and the PC still boots the old disk. Change the boot order.
Restore is refused. The target is smaller than the source.
You cloned onto the backup by reversing the ends. That is the failure the size check is for.

![Foxclone source and destination disks by size](https://www.foxclone.org/images/mirrorfox_transp.png)

## Say the Sizes Out Loud

Foxclone's list is short enough to misread. Before a clone or a restore, say the source size and the target size. The backup disk is the larger external one, or whichever you labeled. The system disk is the one you booted the USB in order to save. If those two sentences are not obvious, unplug every drive except the pair you need.

An image that finishes is still untested until you know the file is on the disk you intended. A clone that finishes has replaced the target. Boot order may still prefer the old disk, which feels like a failed clone when the copy is fine. Change firmware boot order before you repeat the clone.

| Mode | Target becomes |
|---|---|
| Backup to a file | An image on the other disk |
| Clone | A copy of the source, old contents gone |
| Restore | Whatever disk you named, replaced |

Do not use Foxclone to fish a few documents off a disk that still mounts in Windows. Copy the files. Use the boot environment when you need the whole disk and Windows should not be running on it. A failing drive that still opens your folder is a file-copy emergency, not a long image that may die at 90 percent.

## Size, Then the Button

Foxclone's list is short enough to swap the ends. Before a clone or a restore, read the source size and the target size against the disks you labeled. The backup disk is the one you brought. The system disk is the one you booted the USB in order to save. If that is not obvious, unplug every other drive.

A finished clone can still boot the old disk because firmware order did not change. Fix the boot order before you repeat the copy. A finished image is untested until you know which disk holds the file. Restore replaces the named target. A few documents do not need a live environment. Copy them in Windows. A clicking disk that still opens folders should be file-copied before a long image.

- Only the pair of disks you need
- Sizes read aloud
- Image named with the PC and the date
- Boot order checked after a clone
- Restore target read twice
- Extra drives unplugged
- Failing disks not imaged as the first rescue

| Mode | Target |
|---|---|
| Backup | A file on the other disk |
| Clone | The other disk, contents replaced |
| Restore | The disk you named, replaced |

The confirmation line is the product. The progress bar is not a second chance to read it.

## Phrase List

foxclone, foxclone disk image, foxclone backup, foxclone usb, bootable disk clone, foxclone restore, foxclone source target, linux disk clone
