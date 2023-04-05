sendbugs = 'https://forum.mxlinux.org/viewforum.php?f=96'
i18n.gettext(
        gettext_package,
        args: [ '--package-name=@0@'.format(gettext_package),
                '--no-location',
                '--from-code=UTF-8',
                '-c', '-cTRANSLATOR',
                '--join-existing',
                '--no-wrap',
                '--msgid-bugs-address=@0@'.format(sendbugs),
                ],
        preset: 'glib'
        )
