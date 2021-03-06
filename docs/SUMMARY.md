# Summary

* [Guide Overview](overview.md)
* [Terminology](terminology.md)
* [Building and Installing CORD](README.md)
    * [Quickstart](quickstarts.md)
    * [Installing CORD-in-a-Box](install_ciab.md)
    * [Installing a Physical POD](install_pod.md)
        * [Network Settings](appendix_network_settings.md)
        * [Basic Configuration](appendix_basic_config.md)
        * [Container Images](appendix_images.md)
        * [vSG Configuration](appendix_vsg.md)
    * [Connecting to Upstream Networks](vrouter.md)
    * [Build System Internals](build_internals.md)
* [Operating and Managing CORD](operate/README.md)
    * [Configuring XOS](xos/modules/xosconfig.md)
    * [Powering Up a POD](operate/power_up.md)
    * [ELK Stack Logs](operate/elk_stack.md)
    * [REST API](https://guide.opencord.org/{{ book.branch }}/api/xos/)
* [Defining Models in CORD](xos/README.md)
    * [XOS Support for Models](xos/dev/xproto.md)
    * [Core Models](xos/core_models.md)
    * [Security Policies](xos/security_policies.md)
    * [Writing Synchronizers](xos/dev/synchronizers.md)
        * [Design Guidelines](xos/dev/sync_arch.md)
        * [Implementation Details](xos/dev/sync_impl.md)
    * [Migrating Models to 4.0](xos/migrate-4.0.md)
* [Developing for CORD](develop.md)
    * [Getting the Source Code](cord_repo.md)
    * [Workflow: platform-install](platform-install/README.md)
    * [Workflow: local dev](xos/dev/local_env.md)
    * [Example Service](xos/example_service.md)
    * [GUI Development](xos-gui/developer/README.md)
        * [Quickstart](xos-gui/developer/quickstart.md)
        * [Tests](xos-gui/developer/tests.md)
        * [GUI Extensions](xos-gui/developer/gui_extensions.md)
        * [GUI Internals](xos-gui/architecture/README.md)
            * [Module Strucure](xos-gui/architecture/gui-modules.md)
            * [Data Sources](xos-gui/architecture/data-sources.md)
* [Testing CORD](test/README.md)
    * [Running Tests](test/running.md)
    * [List of Tests](test/testcases-listings.md)
* [Service Profiles](service-profiles.md)
    * [R-CORD](profiles/rcord/README.md)
    * [E-CORD](profiles/ecord/README.md)
    * [M-CORD](profiles/mcord/README.md)
    * [OpenCloud](profiles/opencloud/README.md)
* [Release Notes](release-notes/shared-delusion.md)
    * [Jira](release-notes/sd-jira.md)

