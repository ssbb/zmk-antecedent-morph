if ((NOT CONFIG_ZMK_SPLIT) OR CONFIG_ZMK_SPLIT_ROLE_CENTRAL)
  target_sources_ifdef(CONFIG_ZMK_BEHAVIOR_ANTECEDENT_MORPH app PRIVATE behaviors/behavior_antecedent_morph.c)
endif()
