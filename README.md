<?xml version="1.0" encoding="utf-8"?>
<manifest manifest-version="0.1" xmlns="http://www.tableau.com/xml/extension_manifest">
  <worksheet-extension id="com.devizable.extensions.groupeddatatable" extension-version="1.0.0">
    <default-locale>en_US</default-locale>
    <name resource-id="name"/>
    <description>Data table with grouped measures, sticky dimensions, and selectable group display.</description>
    <author name="sandboxed" email="admin@example.com" organization="sandboxed" website="https://github.com"/>
    <min-api-version>1.7</min-api-version>
    <source-location>
      <url>https://example.com/grouped-data-table/index.html</url>
    </source-location>
    <icon>iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR42mNk+M9QDwADhgGAWjR9awAAAABJRU5ErkJggg==</icon>
    <permissions>
      <permission>full data</permission>
    </permissions>
    <context-menu>
      <configure-context-menu-item />
    </context-menu>
  </worksheet-extension>
  <resources>
    <resource id="name">
      <text locale="en_US">Grouped Data Table</text>
    </resource>
  </resources>
</manifest>