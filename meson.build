project('cleanup-notifier-mx', version: '@VERSION@', meson_version: '>=1.0.0')

package_name    = meson.project_name()
desktop_id      = package_name
gettext_package = package_name

po_dir = 'translations/po'

i18n = import('i18n')


subdir('data')

subdir('src')

subdir(po_dir)
