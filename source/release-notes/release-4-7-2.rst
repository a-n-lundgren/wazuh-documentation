.. Copyright (C) 2015, Wazuh, Inc.

.. meta::
  :description: Wazuh 4.7.2 has been released. Check out our release notes to discover the changes and additions of this release.

4.7.2 Release notes - TBD
=========================

This section lists the changes in version 4.7.2. Every update of the Wazuh solution is cumulative and includes all enhancements and fixes from previous releases.

What's new
----------

This release includes new features or enhancements as the following:

Wazuh dashboard
^^^^^^^^^^^^^^^

- `#6191 <https://github.com/wazuh/wazuh-dashboard-plugins/pull/6191>`__ Added **Hostname** and **Board Serial** information to **Agents** > **Inventory data**.
- `#6208 <https://github.com/wazuh/wazuh-dashboard-plugins/pull/6208>`__ Added contextual information to the deploy agent steps.

Resolved issues
---------------

This release resolves known issues as the following: 

Wazuh dashboard
^^^^^^^^^^^^^^^

=================================================================================================================================================    =============
 Reference                                                                                                                                           Description
=================================================================================================================================================    =============
`#6185 <https://github.com/wazuh/wazuh-dashboard-plugins/pull/6185>`__                                                                               Fixed Agents preview page load when there are no registered agents.
`#6206 <https://github.com/wazuh/wazuh-dashboard-plugins/pull/6206>`__, `#6213 <https://github.com/wazuh/wazuh-dashboard-plugins/pull/6213>`__       Changed the endpoint to get Wazuh server auth configuration to ``manager/configuration/auth/auth``.
`#6224 <https://github.com/wazuh/wazuh-dashboard-plugins/pull/6224>`__                                                                               Fixed error navigating back to agent in some scenarios.
=================================================================================================================================================    =============

Changelogs
----------

More details about these changes are provided in the changelog of each component:

- `wazuh/wazuh <https://github.com/wazuh/wazuh/blob/v4.7.2/CHANGELOG.md>`__
- `wazuh/wazuh-dashboard <https://github.com/wazuh/wazuh-dashboard-plugins/blob/v4.7.2-2.8.0/CHANGELOG.md>`__
- `wazuh/wazuh-packages <https://github.com/wazuh/wazuh-packages/releases/tag/v4.7.2>`__
