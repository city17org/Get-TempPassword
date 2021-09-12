# NAME

**Get-TempPassword** - generate a temporary password

# SYNOPSIS

**Get-TempPassword**
\[**-Passwords**&nbsp;*int*]

# DESCRIPTION

**Get-TempPassword**
is a utility that generate a temporary password.
By default, one password will be printed to the terminal.

The options are as follows:

**-Passwords** *int*

> Generate
> *int*
> number of passwords.

# EXAMPLES

	PS C:\> .\Get-TempPassword.ps1 -Passwords 3
	ultr@Lamp23
	goldJ3wel58
	muddyMon+h90

# SEE ALSO

[https://dinopass.com](https://dinopass.com)

# AUTHORS

Sean Davies &lt;[sean@city17.org](mailto:sean@city17.org)&gt;

# CAVEATS

The passwords generated are not secure, nor do they always meet the common
minimum standards of including a lowercase, uppercase, number and special
character.
This utility is solely for service desk members to stop refreshing a web page
and copying the resulting password out.
