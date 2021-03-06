Provisioning Templates
===========================================

Use these options to create Provisioning Templates for Team Sites of different types, or Publishing Apps.

All existing templates are displayed in the list.

.. image:: provisioning-templates-new2.png

Use the icons to edit or delete a template. 

.. image:: provisioning-templates-edit-delete-new2.png

When editing a template, the same options as when creating a template is available, see below.

Create a Provisioning Template
*********************************
To create a Template, do the following:

1. Click the plus.

.. image:: provisioning-templates-create-1new.png

Available settings differ depending on which type of template you're creating, see below.

The first step is the same for all template types. Do the following:

2. For "Base Definition", select "Publishing App" or "Team Collaboration" and use the following settings:

.. image:: provisioning-templates-create-publishing-2new.png

+ **Title**: Add a Title for the Template. You can add titles in a number of the languages available in the tenant. Default language is mandatory.
+ **Description**: Add a Description if needed. You can add titles in a number of the languages available in the tenant. Default language is mandatory.
+ **Icon Type**: An icon is always shown for a Template. If you would like another icon for this Template, select the set of Icons here: "Font Awesome", "Fabric" or "Custom". When selecting "Custom" you can choose any image as the Icon.
+ **Icon**: When you have select Icon Type, use this list to select the icon. If you select "Custom", this list is not shown. Instead a "Url" field is shown, where you enter the Url for the image.
+ **Show in Create New Wizard**: Select this option if the Template should be available in the user Wizard for creating new sites.
+ **Site Creation Mode**: Here you select if if Approval is required when users create sites from this Template. 

3. Click "Next".

For the next steps when you create a template for Team Collaboration, you can set the following:

.. image:: provisioning-templates-create-team-3-new.png

+ **Type**: Select template to base the new template on; "Office 365 Group, Sharepoint Team Site", "Sharepoint Communication Site", "Yammer Group" or "Facebook Workplace Group". This can be changed when an existing Provisioning Template is edited.

The following settings are available for an Office 365 Group:

+ **Site Design**: Here templates can be available, templates made according to Microsoft's standard for Site Design. Such templates can be used in Omnia.  Not mandatory. If no such templates are available, the list is empty. For more information about Site Design, see this Microsoft page: https://docs.microsoft.com/en-us/sharepoint/dev/declarative-customization/site-design-overview
+ **Languages**: Select Language to be used for system texts in the site.
+ **User can select language**: Select this option to enable Language selection by the user creating the site.
+ **Time Zones**: Select the correct Time Zone here.
+ **Location**: Select location for the sites created from this template. For a site collection site, you can select to create sites from this template in any of the managed paths, normally either /sites or /teams. Not available for Office 365 Groups.
+ **Privacy**: For 365 Groups you can select either "Private" or "Public". The text in the selections explains the difference.

The following settings are available for a Sharepoint Team Site and for a Sharepoint Communication Site:

+ **Site Design**: (See above for a description).
+ **Languages**: Select Language to be used for system texts in the site.
+ **User can select language**: Select this option to enable Language selection by the user creating the site.
+ **Time Zones**: Select the correct Time Zone here.
+ **Location**: Select location for the sites created from this template. For a site collection site, you can select to create sites from this template in any of the managed paths, normally either /sites or /teams. Not available for Office 365 Groups.
+ **Primary Site Collection Administrator**: If empty, the user creating or requesting the site will automatically become the Default Administrator (Owner) of the site. If a specific group or user should be administrator for all sites created from this template, add that group or user. Only on group or user can be added in this field.
+ **Default Site Collection Administrators**: You can add (several) additional administrators here, if needed.
+ **Default Visitors**: You can use this to set a default visitor group (read permissions) to all sites created from this template. Let's say it's a template for community pages - then probably all users of the intranet should have read permission to all pages in the site. 

The following setting is available for a Yammer Group Template:

+ **Client id**: Type Client id for the Yammer Network here.

This setting is available for a Facebook Workplace Group Template:

+ **Workplace Domain**: Add the Facebook Workplace name here.

4. When you are done here, Click "Next".

The next step is to select properties, which you can do for all types of templates (but for a Publishing App template theres no need to set any properties at the moment, so just go to the next step). 

All available properties are shown, for example:

.. image:: provisioning-templates-properties-new.png

Available properties must have been set up using the Tenant setting Properties, see: :doc:`Tenant Settings - Properties </admin-settings/tenant-settings/properties/index>`

Normally a lot more properties are available than shown in the image above.

What you can do here is to select if a property should be required (meaning that it should be mandatory to add information for the property when creating a site). For some properties you can also set that multiple values are allowed.

Here's an example with Keywords, where you can set both:

5. Select the property and then click the dot menu.

.. image:: template-properties-dot-menu-new.png

6. Select if the property is required and/or if multiple values should be allowed:

.. image:: template-property-required-new.png

7. Click "Save"
8. When all property settings are done, click "Next", at the bottom of the properties list.

.. image:: provisioning-templates-pubapp4.png

As the next step you can set this:

.. image:: template-features-new.png

+ **Apply Microsoft Teams to an Office 365 Group**: Here you can select that a Microsoft Teams Group should be created for the Office 365 Group.
+ **Create a new Wizard in Document Libraries**: For Document Management; if the New Document Wizard should be added to all document libraries in the site created from this template, check the box.
+ **Controlled Documents Library**: For Document Management; if a Controlled Documents library should be added to all document libraries in the site created from this template, check the box.
+ **Archived Documents**: Select this option if the feature "Archived Documents" should be activated automatically when a site is created from this template.
+ **Project Site**: Select this option if the feature "Project Site" should be activated automatically when a site is created from this template.
+ **Default Page Collections and Page Types**: For Publishing Apps; Select this option if the corresponding feature should be activated automatically when a site is created from this template. The default Page Collections and Page Types can be edited to suit your needs.

**Very important**: Make sure you sellect only the features that are applicable for the type of template you create, if any. Selecting the wrong feature here can cause problems when a site is created from the template. For example is only te feature at the bottom applicable for Publishing App templates.

9. Set the options here as needed and click "Next".

Finally, you can select to add Custom Steps. If you do, something like the following is shown:

.. image:: custom-steps.png

You can choose to add some standard "Custom steps" as shown in the image above. If additional Custom Steps are developed, they are shown here.

10. When all settings are done here, or if you selected not to add custom steps, click "ADD" to create the Template.

.. image:: provisioning-templates-4-new.png