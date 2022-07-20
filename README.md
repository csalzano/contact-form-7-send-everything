![Contact Form 7 - Send Everything](assets/banner-1544x500.jpg)

# contact-form-7-send-everything

WordPress plugin. Extension for Contact Form 7. Adds a mail-tag <code>[everything]</code> that sends all fields in the message body.

## Filter Hooks

* `wpcf7_send_everything_empty_fields` Exclude empty fields, boolean
* `wpcf7_send_everything_title` Change the title at the top of the email body, string
* `wpcf7_send_everything_title_meta` Change the title of the second metadata table, string
* `wpcf7_send_everything_css_font` Change the font-family, string
* `wpcf7_send_everything_table_open` Edit the \<table> table open tag, string
* `wpcf7_send_everything_table_close` Edit the \</table> table close tag, string
* `wpcf7_send_everything_table_row` Change \<tr> table row elements, string
* `wpcf7_send_everything_format_labels` Disable title-case field labels, boolean
* `wpcf7_send_everything_label` Change field label text, string
* `wpcf7_send_everything_link_urls` Disable linked URLs, boolean