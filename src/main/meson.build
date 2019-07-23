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



exe_src = [ 'main.go' ]



custom_target('exe',
    output : 'exe',
    input : exe_src,
    command : ['go', 'build', '@INPUT@'],
    build_by_default: true)
