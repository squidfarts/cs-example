###################################################################################
#                                                                                 #
# NAME: meson.build                                                               #
#                                                                                 #
# AUTHOR: Michael Brockus.                                                        #
#                                                                                 #
# CONTACT: <mailto:michael@squidfarts.com>                                        #
#                                                                                 #
# NOTICES:                                                                        #
#                                                                                 #
# License: MIT                                                                    #
#                                                                                 #
###################################################################################



project('c#-example', 'cs',
    version         : '0.1.0',
    license         : 'MIT',
    meson_version   : '>=0.50.0')

subdir('src')

install_data(
    sources: [ 'code_of_conduct.md', 'license.md', 'readme.md' ],
    install_dir: join_paths(get_option('datadir'), meson.project_name()))