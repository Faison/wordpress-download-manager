WordPress Download Manager
=============================

A parallel version of [the plugin located in the WordPress Plugin Directory](http://wordpress.org/plugins/download-manager/).

This version adds two quick enhancements that I offered the code for [here](http://wordpress.org/support/topic/add-ability-to-filter-user-authentication-check-1?replies=5), but even though the plugin author said he'd add it, nothing. So taking advantage of the rights we have with Free Software, I created this fork.

This fork adds two filters: `wpdm_does_user_need_to_login` and `wpdm_login_url`. Before adding the first filter, the only way protected downloads could be downloaded is if a user is logged into WordPress, but now you can hook in and allow people logged into 3rd party services to download those files. The second filter was needed because the downloads that require login would direct users to the WordPress login, so now you can direct the user to your 3rd party login page instead.

So install this plugin version of the plugin if you want those filters. If the plugin author ever adds my changes to his code, I'll put a message at the top of this repo.