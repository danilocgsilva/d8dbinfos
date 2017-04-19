# d8dbinfos

Use it sourcing.

Your script must already have a variable called $drupal8_settings_path, and will generate $drupal_database_name, $drupal_database_user, $drupal_database_pass, $drupal_database_host, $drupal_database_prefix.

Works only in the most simplest drupal installations. If there's more than a single database setted, it will be expected unexpected behaviour, fetching the frist one setted.