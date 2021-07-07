# heroku-configvar-files-buildpack
Writes Heroku config vars values to file

## Configuration
In root of repo, create a file named heroku-configvar-files-buildpack-config.
In this config file, provide a config var name and map it to a file name.  Map multiple files on separate lines.

Example:
```
MY_CONFIG_VAR:my_config_var_file
SECRET_API_KEY:api_key
```
