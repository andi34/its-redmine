gerrit_plugin(
  name = 'its-redmine',
  srcs = glob(['src/main/java/org/cyrilix/gerrit/plugins/**/*.java']),
  manifest_entries = [
    'Gerrit-Module: org.cyrilix.gerrit.plugins.redmine.RedmineModule',
    'Gerrit-InitStep: org.cyrilix.gerrit.plugins.redmine.InitRedmine',
    'Gerrit-ReloadMode: reload',
    'Implementation-Title: Redmine ITS Plugin',
    'Implementation-URL: http://www.gerritforge.com',
    'Implementation-Vendor: Cyrille Nofficial',
  ],
  deps = [
    '//plugins/its-base:its-base__plugin',
    '//plugins/its-redmine/lib:redmine-java-api',
    '//plugins/its-redmine/lib:logback-classic',
    '//plugins/its-redmine/lib:easymock'
],
)
