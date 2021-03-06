Upcoming Release 4.0.0 (Draft) 
========================================
*NOTE: These release notes are a draft. Items might be added, altered or removed.*


New features
----------------------------------------
- Omnia Process Management
- Communities 2.0
- Improvements on Team Collaboration listings (#116996, #114661, #114870, #117577, #114837, #116854).
 - Possible to remove Team Collaborations when there is an error or the O365 group is already deleted. (#117576).
- Search experience in header and as a block.
- Action button has recieved many updates multilingual support has been improved and it can now be used to create pages (#117303, #114101).
- Pexels as a new Image provider (Please note that this not supported for IE11)
- Translation workflow
- Improved Audit Logging UI
- Enhanced Document Picker
- User Profile Sync


Enhancements
------------------------------------

Omnia
***********************
- Fixes to remove certificate error in Firefox.
- Several fixes to align with WCAG 2.1 AA.
- Improved keyboard controls.
- Several performance improvements for both Omnia and SPFx.
- Stability improvements to the color picker.

Web Content Management
***********************
- Now possible to use @mentions in page comments. An email will be sent to the mentioned user. (#113114)
- New Tab Section component, use it to create tabbed views on your pages.
- Deleting a page now gives correct UI feedback.
- Ensured correct label on the edit link and edit header in related links.
- Picking a document in related links can now support libraries with more than 5000 documents. 
- Auto rolling of the news roller will be disabled if accessibility mode is turned on.
- Custom block header size now starts at 1px instead of 30px.
- The page rollup now works correctly in SPFx (#118051).

Document Management
***********************
- Support for vsdx icons.
- The Tabs Drafts, Tasks, and Published now has a larger click area (#117861).

Tenant Administration
***********************
- Better handling for long display names on enterprise properties. (#114375, #114783, #117172).

Workplace
***********************
- It is now possible to base search queries on page variation url segment. 
- Targeting for search categories. It is now possible to use the targeting engine on search categories. (#115142, #115263).
- Date refiners now work as expected in advanced search (#114577, #115570).
- Updated design in advanced search (#117305, #116824).
- Updated design for action bar item tabs.
- Updated design for shared links.

Fixes 
***********************
- Fixed a design glitch in document libraries when the omnia header is used. 
- People rollup roller view not auto rotates correctly (#117277).
- Page rollup column adjustment now works when having only one column (#117154, #117304).
- Correct default setting on date format when setting up a new environment (#114587).
- Several fixes to the document rollup, including taxonomy properties now work correctly in the query builder (#117598).
- Fixed an issue when related links settings would be unavailable after adding a link (#117580).
- Corrected email content from comment on important announcement (#117825).
- Background color on Shared Links is now set correctly when using the color picker to remove the color (#117646).
- Site Design is now hidden from the end user when creating a site (#113598).
- Improvements to term picker in dialogs.
- Fixed a problem that would cause the browser to hang if resized.
- Fixed alignment of top header for nodes without children.
- Fixed a z-index problem that would sometimes occur in SPFx.
- Padding now works as expected on the button link (#116905).
- Fixed a problem in the term picker for controlled documents (#117247).
- Fixes to the document rollup query builder to have better default values.
- Several fixes to margins and padding on the action button.
- Fixes to block margins, border radius and breadcrumb margins (#117653).
- Placeholder behavior is now correct on the accordion.
- Corrected UI in Document Management authoring sites to make tick boxes align (#117430).
- Corrected mobile navigation when using multiple page collections in one navigation structure (#115759).
- Document rollup now shows sorting arrows correctly when sorting (#117793, #118277).
- Document rollup now correctly hides when there is no content in the rollup (#117827).
- Advanced search now always shows the correct item count. Also impacts results and paging in some scenarios (#114072, #115352, #116723, #114039, #115789, #117802, #115121, #115250).
- External links in Shared Links now work correctly on IOS (#117048).
- Adding documents through related links now correctly lists deleted users (#117801).
- Now possible to create two enterprise properties with the same displayname (#115627).
- Fixed the page properties block to correctly rowbreak properties that does not fit (#118275).






