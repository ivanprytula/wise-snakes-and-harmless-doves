# wise-snakes-and-harmless-doves
Web, single-/multiplayer board-like strategy game (2D), turn-based/simultaneously played

## Game type to choose:
- eco tycoon
- kingdom-like (units, resources, buildings, nature/trees, rocks, enemies), units - as cards(models) with properties
- snake & ladder

## High-level game/features description
### [TOC]
- [x] main idea-1: the first who reaches finish - is the winner
- [x] main idea-2:
- [ ] host can select diff background picture & other styles (aka "world") (for fun)
- [ ] ladder tiles (html+css OR canvas) | map with many roads (things have to be interactive to play the game) - let's use, maybe, some algorithm as "skeleton" >> for future better configuration/search
- [ ] track time for game/user move - user can solve a puzzle to get more time to think;
- [ ] roll a dice to choose users' movement steps,
- [ ] each user select his/her starting "hero" w/ specific skills: HP, strength, shield, soft skills?
- [ ] API<-->UI w/ many urls
- [ ] each tile/spot on "map" will have different tasks/features -> get points for solving/bad or good creatures - fight with them, or they can give user some stuff
- [ ] chat (text/voice) in game for communication
- [ ] cards for 'heroes' and tiles

 Clean initial `migrate` command
 ```shell
Operations to perform:
  Apply all migrations: account, admin, auth, authtoken, contenttypes, sessions, sites, socialaccount, users
Running migrations:
  Applying contenttypes.0001_initial... OK
  Applying contenttypes.0002_remove_content_type_name... OK
  Applying auth.0001_initial... OK
  Applying auth.0002_alter_permission_name_max_length... OK
  Applying auth.0003_alter_user_email_max_length... OK
  Applying auth.0004_alter_user_username_opts... OK
  Applying auth.0005_alter_user_last_login_null... OK
  Applying auth.0006_require_contenttypes_0002... OK
  Applying auth.0007_alter_validators_add_error_messages... OK
  Applying auth.0008_alter_user_username_max_length... OK
  Applying auth.0009_alter_user_last_name_max_length... OK
  Applying auth.0010_alter_group_name_max_length... OK
  Applying auth.0011_update_proxy_permissions... OK
  Applying auth.0012_alter_user_first_name_max_length... OK
  Applying users.0001_initial... OK
  Applying account.0001_initial... OK
  Applying account.0002_email_max_length... OK
  Applying admin.0001_initial... OK
  Applying admin.0002_logentry_remove_auto_add... OK
  Applying admin.0003_logentry_add_action_flag_choices... OK
  Applying authtoken.0001_initial... OK
  Applying authtoken.0002_auto_20160226_1747... OK
  Applying authtoken.0003_tokenproxy... OK
  Applying sessions.0001_initial... OK
  Applying sites.0001_initial... OK
  Applying sites.0002_alter_domain_unique... OK
  Applying sites.0003_set_site_domain_and_name... OK
  Applying sites.0004_alter_options_ordering_domain... OK
  Applying socialaccount.0001_initial... OK
  Applying socialaccount.0002_token_max_lengths... OK
  Applying socialaccount.0003_extra_data_default_dict... OK

```
