# List of Conditional Tags


## <span id="complete-list-of-template-tags">Complete List of Template Tags</span> [#](complete-list-of-template-tags)

Template tags files are stored in the wp-includes directory. The files have the suffix of “-template.php” to distinguish them from other WordPress files. There are 9 template tags files:

- [wp-includes/general-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/general-template.php#L0)
- [wp-includes/author-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/author-template.php#L0)
- [wp-includes/bookmark-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/bookmark-template.php#L0)
- [wp-includes/category-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/category-template.php#L0)
- [wp-includes/comment-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/comment-template.php#L0)
- [wp-includes/link-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/link-template.php#L0)
- [wp-includes/post-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/post-template.php#L0)
- [wp-includes/post-thumbnail-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/post-thumbnail-template.php#L0)
- [wp-includes/nav-menu-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/nav-menu-template.php#L0)

<p style="text-arign: right;">[Top](#top)</p>

## <span id="tags">Tags</span> [#](#tags)

### <span id="#general-tags">General tags</span> [#](#general-tags)

[wp-includes/general-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/general-template.php#L0)

- [get_header()](https://developer.wordpress.org/reference/functions/get_header/)
- [get_footer()](https://developer.wordpress.org/reference/functions/get_footer/)
- [get_sidebar()](https://developer.wordpress.org/reference/functions/get_sidebar/)
- [get_template_part()](https://developer.wordpress.org/reference/functions/get_template_part/)
- [get_search_form()](https://developer.wordpress.org/reference/functions/get_search_form)
- [wp_loginout()](https://developer.wordpress.org/reference/functions/wp_loginout/)
- [wp_logout_url()](https://developer.wordpress.org/reference/functions/wp_logout_url/)
- [wp_login_url()](https://developer.wordpress.org/reference/functions/wp_login_url/)
- [wp_login_form()](https://developer.wordpress.org/reference/functions/wp_login_form/)
- [wp_lostpassword_url()](https://developer.wordpress.org/reference/functions/wp_lostpassword_url/)
- [wp_register()](https://developer.wordpress.org/reference/functions/wp_register/)
- [wp_meta()](https://developer.wordpress.org/reference/functions/wp_meta/)
- [bloginfo()](https://developer.wordpress.org/reference/functions/bloginfo/)
- [get_bloginfo()](https://developer.wordpress.org/reference/functions/get_bloginfo/)
- [get_current_blog_id()](https://developer.wordpress.org/reference/functions/get_current_blog_id)
- [wp_title()](https://developer.wordpress.org/reference/functions/wp_title)
- [single_post_title()](https://developer.wordpress.org/reference/functions/single_post_title)
- [post_type_archive_title()](https://developer.wordpress.org/reference/functions/post_type_archive_title)
- [single_cat_title()](https://developer.wordpress.org/reference/functions/single_cat_title)
- [single_tag_title()](https://developer.wordpress.org/reference/functions/single_tag_title)
- [single_term_title()](https://developer.wordpress.org/reference/functions/single_term_title)
- [single_month_title()](https://developer.wordpress.org/reference/functions/single_month_title)
- [get_archives_link()](https://developer.wordpress.org/reference/functions/get_archives_link)
- [wp_get_archives()](https://developer.wordpress.org/reference/functions/wp_get_archives)
- [calendar_week_mod()](https://developer.wordpress.org/reference/functions/calendar_week_mod)
- [get_calendar()](https://developer.wordpress.org/reference/functions/get_calendar)
- [delete_get_calendar_cache()](https://developer.wordpress.org/reference/functions/delete_get_calendar_cache/)
- [allowed_tags()](https://developer.wordpress.org/reference/functions/allowed_tags/)
- [wp_enqueue_script()](https://developer.wordpress.org/reference/functions/wp_enqueue_script)

[Top](#top)

## <span id="author-tags">Author tags</span> [#](#author-tags)

[wp-includes/author-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/author-template.php#L0)

- [the_author(https://developer.wordpress.org/reference/functions/the_author)]()
- [get_the_author(https://developer.wordpress.org/reference/functions/get_the_author)]()
- [the_author_link(https://developer.wordpress.org/reference/functions/the_author_link)]()
- [get_the_author_link(https://developer.wordpress.org/reference/functions/get_the_author_link)]()
- [the_author_meta(https://developer.wordpress.org/reference/functions/the_author_meta)]()
- [the_author_posts(https://developer.wordpress.org/reference/functions/the_author_posts)]()
- [the_author_posts_link(https://developer.wordpress.org/reference/functions/the_author_posts_link)]()
- [wp_dropdown_users(https://developer.wordpress.org/reference/functions/wp_dropdown_users)]()
- [wp_list_authors(https://developer.wordpress.org/reference/functions/wp_list_authors)]()
- [get_author_posts_url(https://developer.wordpress.org/reference/functions/get_author_posts_url)]()

[Top](#top)

## <span id="bookmark-tags">Bookmark tags</span> [#](#bookmark-tags)

[wp-includes/bookmark-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/bookmark-template.php#L0) and [wp-includes/bookmark.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/bookmark.php#L0)

- [wp_list_bookmarks(https://developer.wordpress.org/reference/functions/wp_list_bookmarks)]()
- [get_bookmark(https://developer.wordpress.org/reference/functions/get_bookmark)]()
- [get_bookmark_field(https://developer.wordpress.org/reference/functions/get_bookmark_field)]()
- [get_bookmarks(https://developer.wordpress.org/reference/functions/get_bookmarks)]()

[Top](#top)

## <span id="category-tags">Category tags</span> [#](#category-tags)

[wp-includes/category-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/category-template.php#L0)

- [category_description()](https://developer.wordpress.org/reference/functions/category_description)
- [single_cat_title()](https://developer.wordpress.org/reference/functions/single_cat_title)
- [the_category()](https://developer.wordpress.org/reference/functions/the_category)
- [the_category_rss()](https://developer.wordpress.org/reference/functions/the_category_rss)
- [wp_dropdown_categories()](https://developer.wordpress.org/reference/functions/wp_dropdown_categories)
- [wp_list_categories()](https://developer.wordpress.org/reference/functions/wp_list_categories/)
- [single_tag_title()](https://developer.wordpress.org/reference/functions/single_tag_title)
- [tag_description()](https://developer.wordpress.org/reference/functions/tag_description)
- [the_tags()](https://developer.wordpress.org/reference/functions/the_tags)
- [wp_generate_tag_cloud()](https://developer.wordpress.org/reference/functions/wp_generate_tag_cloud)
- [wp_tag_cloud()](https://developer.wordpress.org/reference/functions/wp_tag_cloud)
- [term_description()](https://developer.wordpress.org/reference/functions/term_description)
- [single_term_title()](https://developer.wordpress.org/reference/functions/single_term_title)
- [get_the_term_list()](https://developer.wordpress.org/reference/functions/get_the_term_list)
- [the_terms()](https://developer.wordpress.org/reference/functions/the_terms)
- [the_taxonomies()](https://developer.wordpress.org/reference/functions/the_taxonomies)

[Top](#top)

## <span id="comment-tags">Comment tags</span> [#](#comment-tags)

[wp-includes/comment-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/comment-template.php#L0)

- [cancel_comment_reply_link()](https://developer.wordpress.org/reference/functions/cancel_comment_reply_link)
- [comment_author()](https://developer.wordpress.org/reference/functions/comment_author)
- [comment_author_email()](https://developer.wordpress.org/reference/functions/comment_author_email)
- [comment_author_email_link()](https://developer.wordpress.org/reference/functions/comment_author_email_link)
- [comment_author_IP()](https://developer.wordpress.org/reference/functions/comment_author_IP)
- [comment_author_link()](https://developer.wordpress.org/reference/functions/comment_author_link)
- [comment_author_rss()](https://developer.wordpress.org/reference/functions/comment_author_rss)
- [comment_author_url()](https://developer.wordpress.org/reference/functions/comment_author_url)
- [comment_author_url_link()](https://developer.wordpress.org/reference/functions/comment_author_url_link)
- [comment_class()](https://developer.wordpress.org/reference/functions/comment_class)
- [comment_date()](https://developer.wordpress.org/reference/functions/comment_date)
- [comment_excerpt()](https://developer.wordpress.org/reference/functions/comment_excerpt)
- [comment_form_title()](https://developer.wordpress.org/reference/functions/comment_form_title)
- [comment_form()](https://developer.wordpress.org/reference/functions/comment_form)
- [comment_ID()](https://developer.wordpress.org/reference/functions/comment_ID)
- [comment_id_fields()](https://developer.wordpress.org/reference/functions/comment_id_fields)
- [comment_reply_link()](https://developer.wordpress.org/reference/functions/comment_reply_link)
- [comment_text()](https://developer.wordpress.org/reference/functions/comment_text)
- [comment_text_rss()](https://developer.wordpress.org/reference/functions/comment_text_rss)
- [comment_time()](https://developer.wordpress.org/reference/functions/comment_time)
- [comment_type()](https://developer.wordpress.org/reference/functions/comment_type)
- [comments_link()](https://developer.wordpress.org/reference/functions/comments_link)
- [comments_number()](https://developer.wordpress.org/reference/functions/comments_number)
- [comments_popup_link()](https://developer.wordpress.org/reference/functions/comments_popup_link)
- [get_avatar()](https://developer.wordpress.org/reference/functions/get_avatar)
- [next_comments_link()](https://developer.wordpress.org/reference/functions/next_comments_link)
- [paginate_comments_links()](https://developer.wordpress.org/reference/functions/paginate_comments_links)
- [permalink_comments_rss()](https://developer.wordpress.org/reference/functions/permalink_comments_rss)
- [previous_comments_link()](https://developer.wordpress.org/reference/functions/previous_comments_link)
- [wp_list_comments()](https://developer.wordpress.org/reference/functions/wp_list_comments)

[Top](#top)

## <span id="link-tags">Link tags</span> [#](#link-tags)

[wp-includes/link-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/link-template.php#L0)

- [the_permalink()](https://developer.wordpress.org/reference/functions/the_permalink)
- [user_trailingslashit()](https://developer.wordpress.org/reference/functions/user_trailingslashit)
- [permalink_anchor()](https://developer.wordpress.org/reference/functions/permalink_anchor)
- [get_permalink()](https://developer.wordpress.org/reference/functions/get_permalink)
- [get_post_permalink()](https://developer.wordpress.org/reference/functions/get_post_permalink)
- [get_page_link()](https://developer.wordpress.org/reference/functions/get_page_link)
- [get_attachment_link()](https://developer.wordpress.org/reference/functions/get_attachment_link)
- [wp_shortlink_header()](https://developer.wordpress.org/reference/functions/wp_shortlink_header/)
- [wp_shortlink_wp_head()](https://developer.wordpress.org/reference/functions/wp_shortlink_wp_head/)
- [edit_bookmark_link()](https://developer.wordpress.org/reference/functions/edit_bookmark_link)
- [edit_comment_link()](https://developer.wordpress.org/reference/functions/edit_comment_link)
- [edit_post_link()](https://developer.wordpress.org/reference/functions/edit_post_link)
- [get_edit_post_link()](https://developer.wordpress.org/reference/functions/get_edit_post_link/)
- [get_delete_post_link()](https://developer.wordpress.org/reference/functions/get_delete_post_link)
- [edit_tag_link()](https://developer.wordpress.org/reference/functions/edit_tag_link)
- [get_admin_url()](https://developer.wordpress.org/reference/functions/get_admin_url)
- [get_home_url()](https://developer.wordpress.org/reference/functions/get_home_url)
- [get_site_url()](https://developer.wordpress.org/reference/functions/get_site_url)
- [home_url()](https://developer.wordpress.org/reference/functions/home_url)
- [site_url()](https://developer.wordpress.org/reference/functions/site_url)
- [get_search_link()](https://developer.wordpress.org/reference/functions/get_search_link)
- [get_search_query()](https://developer.wordpress.org/reference/functions/get_search_query)
- [the_feed_link()](https://developer.wordpress.org/reference/functions/the_feed_link)

[Top](#top)

## <span id="post-tags">Post tag</span> [#](#post-tags)

[wp-includes/post-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/post-template.php#L0)

- [body_class()](https://developer.wordpress.org/reference/functions/body_class)
- [next_image_link()](https://developer.wordpress.org/reference/functions/next_image_link)
- [next_post_link()](https://developer.wordpress.org/reference/functions/next_post_link)
- [next_posts_link()](https://developer.wordpress.org/reference/functions/next_posts_link)
- [post_class()](https://developer.wordpress.org/reference/functions/post_class)
- [post_password_required()](https://developer.wordpress.org/reference/functions/post_password_required)
- [posts_nav_link()](https://developer.wordpress.org/reference/functions/posts_nav_link)
- [previous_image_link()](https://developer.wordpress.org/reference/functions/previous_image_link)
- [previous_post_link()](https://developer.wordpress.org/reference/functions/previous_post_link)
- [previous_posts_link()](https://developer.wordpress.org/reference/functions/previous_posts_link)
- [single_post_title()](https://developer.wordpress.org/reference/functions/single_post_title)
- [the_category()](https://developer.wordpress.org/reference/functions/the_category)
- [the_category_rss()](https://developer.wordpress.org/reference/functions/the_category_rss)
- [the_content()](https://developer.wordpress.org/reference/functions/the_content)
- [the_excerpt()](https://developer.wordpress.org/reference/functions/the_excerpt)
- [the_excerpt_rss()](https://developer.wordpress.org/reference/functions/the_excerpt_rss)
- [the_ID()](https://developer.wordpress.org/reference/functions/the_ID)
- [the_meta()](https://developer.wordpress.org/reference/functions/the_meta)
- [the_tags()](https://developer.wordpress.org/reference/functions/the_tags)
- [the_title()](https://developer.wordpress.org/reference/functions/the_title)
- [get_the_title()](https://developer.wordpress.org/reference/functions/get_the_title)
- [the_title_attribute()](https://developer.wordpress.org/reference/functions/the_title_attribute)
- [the_title_rss()](https://developer.wordpress.org/reference/functions/the_title_rss)
- [wp_link_pages()](https://developer.wordpress.org/reference/functions/wp_link_pages)
- [get_attachment_link()](https://developer.wordpress.org/reference/functions/get_attachment_link)
- [wp_get_attachment_link()](https://developer.wordpress.org/reference/functions/wp_get_attachment_link)
- [the_attachment_link()](https://developer.wordpress.org/reference/functions/the_attachment_link)
- [the_search_query()](https://developer.wordpress.org/reference/functions/the_search_query)
- [is_attachment()](https://developer.wordpress.org/reference/functions/is_attachment)
- [wp_attachment_is_image()](https://developer.wordpress.org/reference/functions/wp_attachment_is_image)
- [wp_get_attachment_image()](https://developer.wordpress.org/reference/functions/wp_get_attachment_image)
- [wp_get_attachment_image_src()](https://developer.wordpress.org/reference/functions/wp_get_attachment_image_src)
- [wp_get_attachment_metadata()](https://developer.wordpress.org/reference/functions/wp_get_attachment_metadata)
- [get_the_date()](https://developer.wordpress.org/reference/functions/get_the_date)
- [single_month_title()](https://developer.wordpress.org/reference/functions/single_month_title)
- [the_date()](https://developer.wordpress.org/reference/functions/the_date)
- [the_date_xml()](https://developer.wordpress.org/reference/functions/the_date_xml)
- [the_modified_author()](https://developer.wordpress.org/reference/functions/the_modified_author)
- [the_modified_date()](https://developer.wordpress.org/reference/functions/the_modified_date)
- [the_modified_time()](https://developer.wordpress.org/reference/functions/the_modified_time)
- [the_time()](https://developer.wordpress.org/reference/functions/the_time)
- [the_shortlink()](https://developer.wordpress.org/reference/functions/the_shortlink)
- [wp_get_shortlink()](https://developer.wordpress.org/reference/functions/wp_get_shortlink)

[Top](#top)

## <span id="post-thumbnail-tags">Post Thumbnail tags</span> [#](#post-thumbnail-tags)

[wp-includes/post-thumbnail-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/post-thumbnail-template.php#L0)

- [has_post_thumbnail()](https://developer.wordpress.org/reference/functions/has_post_thumbnail)
- [get_post_thumbnail_id()](https://developer.wordpress.org/reference/functions/get_post_thumbnail_id)
- [the_post_thumbnail()](https://developer.wordpress.org/reference/functions/the_post_thumbnail)
- [get_the_post_thumbnail()](https://developer.wordpress.org/reference/functions/get_the_post_thumbnail)

[Top](#top)

## <span id="navigation-menu-tags">Navigation Menu tags</span> [#](#navigation-menu-tags)

[wp-includes/nav-menu-template.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/nav-menu-template.php#L0)

- [wp_nav_menu()](https://developer.wordpress.org/reference/functions/wp_nav_menu)
- [walk_nav_menu_tree()](https://developer.wordpress.org/reference/functions/walk_nav_menu_tree/)

[Top](#top)

## <span id="see-also">See Also</span> [#](#see-also)

- [Conditional Tags](https://developer.wordpress.org/themes/basics/conditional-tags/)