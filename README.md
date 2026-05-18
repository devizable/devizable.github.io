<?xml version="1.0" encoding="utf-8"?>
<manifest manifest-version="0.1" xmlns="http://www.tableau.com/xml/extension_manifest">
  <dashboard-extension id="com.devizable.extensions.exceltemplate" extension-version="1.0.0">
    <default-locale>en_US</default-locale>
    <name resource-id="name"/>
    <description>Populate an Excel template with live worksheet data, with optional formula flattening on download.</description>
    <author name="sandboxed" email="admin@example.com" organization="sandboxed" website="https://github.com"/>
    <min-api-version>1.7</min-api-version>
    <source-location>
      <url>https://example.com/excel-template/index.html</url>
    </source-location>
    <icon>iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR42mNk+M9QDwADhgGAWjR9awAAAABJRU5ErkJggg==</icon>
    <permissions>
      <permission>full data</permission>
    </permissions>
    <context-menu>
      <configure-context-menu-item />
    </context-menu>
  </dashboard-extension>
  <resources>
    <resource id="name">
      <text locale="en_US">Excel Template</text>
    </resource>
  </resources>
</manifest>