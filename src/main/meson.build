###################################################################################
#                                                                                 #
# NAME: src/main/meson.build                                                      #
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



exe_inc = []
exe_src = [ 'main.cs' ]



exe_main = executable('exe', 
    sources: [ exe_src, exe_inc ],
    include_directories: exe_dir,
    install: true)



test('Test exe', exe_main)