# Sparrowdo::VSTS::YAML:Nuget

Sparrowdo module to generate VSTS yaml steps for nuget package manager.

    $ cat sparrowfile

    # Run nuget restore for project located in $work-folder
    module_run "VSTS::YAML::Nuget", %(
      working-folder => "app/foo", # path to project
      solution => "app.sln", # path to solution file, default value
    );

    $ sparrowdo --local_mode --no_sudo

# Author

Alexey Melezhik

