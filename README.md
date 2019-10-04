###confluence.rb

Helper script to access Atlassian Confluence. Currently you can

* create and update pages
* read page information (version, labels, space key, ...)

Usage
-----

Usage: confluence.rb [options]
    -c, --create_page PARENT_URL     Create page. 
    -d, --get_details PAGE_URL       Get page details (ID and space)
    -f, --content_file FILENAME      Content to upload
    -s, --search_user USERNAME       Search user
    -t, --page_title TITLE           Page title for new or updated pages
    -u, --update_page PAGE_URL       Update page, set also title (-t) and content (-f)
    -v, --verbose                    Run verbosely
    -h, --help                       Prints this help