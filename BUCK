include_defs('//bucklets/gerrit_plugin.bucklet')

MODULE = 'com.googlesource.gerrit.plugins.github.replication'

gerrit_plugin(
  name = 'github-replication',
  srcs = glob(['src/main/java/**/*.java']),
  resources = glob(['src/main/**/*']),
  manifest_entries = [
    'Gerrit-PluginName: github-replication',
    'Gerrit-Module: com.googlesource.gerrit.plugins.github.replication.Module',
    'Implementation-Title: GitHub Replication wizard',
    'Implementation-URL: https://gerrit-review.googlesource.com/#/admin/projects/plugins/github-replication',
  ],
)
