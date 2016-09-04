# teneo third party dependencies
This repository includes all the thirdparty dependencies required by the org.eclipse.emf.teneo project. The teneotexodeps
is the update site project that consists of the final artifacts and plugins.

This repo was originally created out of the workspace for *Eclipse for RCP and RAP Developers Version: Juno Service Release 2*.

### Build
1. Once imported projects have been modified, the `teneotexodeps` update site project can be used to re-build all the
features and plugins
2. Make sure `site.xml` is up-to-date, clicking the `Synchronize` button doesn't hurt
3. Click `Build All` to regenerate everything
4. If projects were renamed/removed, older jars will still be present so deleting everything except the `.project` and the `site.xml`,
then building will make sure everything is in place and old jars are not present
