# Changes in 0.3.1

# Changes in 0.3.0

-   Exit on error

-   Let failed operations be an error

-   Fix existence check for variable

-   Add support for custom basedir

-   Let programm execute as different user

-   Make --root deprecated

-   Change ownership only if flag is given

-   Support custom directory separator

-   Change to input directory before anything else

    This ensures that relative paths as --basedir are resolved correctly.

# Changes in 0.2.1

-   Create directory first before copying

-   Create directory first before linking

# Changes in 0.2.0

-   Rename message variable to avoid confusions

    The message variable in the output methods are strings and should not be
    confused with the global array with the same name.

-   Add -r option to read

    Read should always be called with -r to avoid interpreting special
    characters.

-   Set pwd earlier in the script

-   Copy non-existent items first

    If the destination exists but the source file does not, copy it first
    before linking.

# Changes in 0.1.0

Initial release.
