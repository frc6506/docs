# Driver Station Overview

> `docs.steelbootrobotics.org/ds` and `frc6506.github.io/docs/ds` redirect here

## Important Guides

> These cover how to prepare the driver station laptop for competition, final setup, and cleanup for general sue.

| Guide | When to use | Purpose |
|---|---|---|
| [Pre Competition](guides/preCompetition) | During build season, _two weeks to a month before_ competition |
| [At Competition](guides/atCompetition) | Upon arrival to a competition | Final preparations to ensure optimal performance |
| [Post Competition](guides/postCompetition) | Upon return from competition before connecting to the internet | Return the laptop to a secure state that is safe to connect to the internet in order to perform updates |

### Other Guides

> These include more general information

| Guide | Purpose |
|---|---|
| [Laptop](guides/laptop) | General information about using a Windows laptop, specially our Dell Latitude 3480 |
| [Windows](guides/windows) | General guide to how to use Windows, in particular as configured on our Dell Latitude 3480 |
| [Template](guides/template); [GitHub link](https://github.com/frc6506/docs/blob/master/driverStation/guides/template.md) | This is just a template for guides. |

## Maintenance

## Know Problems

| Description | Mitigation / Work Around | Date Discovered | Notes |
|---|---|---|---|
| "Alert! TPM device not detected" _warning on boot_ | Press [C] or click `Continue` to ignore the warning | Before 05/01/2022 | Started occurring after BIOS update via Dell Command Update.  It is possible to disable warnings, but that seems like a bad idea. |
| _Ethernet cable loose_ OR _intermediate ethernet disconnect_. | _Use a USB - $J-45 ethernet adapter_ | Before 05/01/2022 | According to an FTA, the ethernet port is going bad.  The cable is actually able to wiggle in and out of the RJ-45 port.  I have also noticed the port's trim seems a bit warped.  _DO NOT USE the RJ-45 ethernet port_ |

<br>

[Driver Station Docs Overview](https://frc6506.github.io/docs/driverStation/overview)

[Docs Site Index](https://frc6506.github.io/docs/index)

<br>

_Updated 20220512T2145 PT_
