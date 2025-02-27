<!--
This file was generated by Spark. Do not edit it by hand.
-->
# DSL: AshAdmin.Domain

An API extension to alter the behavior of an API in the admin UI.


## admin
Configure the admin dashboard for a given API.






### Options

| Name | Type | Default | Docs |
|------|------|---------|------|
| [`name`](#admin-name){: #admin-name } | `String.t` |  | The name of the API in the dashboard. Will be derived if not set. |
| [`show?`](#admin-show?){: #admin-show? } | `boolean` | `false` | Whether or not this API and its resources should be included in the admin dashboard. |
| [`default_resource_page`](#admin-default_resource_page){: #admin-default_resource_page } | `:schema \| :primary_read` | `:schema` | Set the default page for the resource to be the primary read action or the resource schema. Schema is the default for backwards compatibility, if a resource doesn't have a primary read action it will fallback to the schema view. |
| [`resource_group_labels`](#admin-resource_group_labels){: #admin-resource_group_labels } | `keyword` | `[]` | Humanized names for each resource group to appear in the admin area. These will be used as labels in the top navigation dropdown. If a key for a group does not appear in this mapping, the label will not be rendered. |







<style type="text/css">.spark-required::after { content: "*"; color: red !important; }</style>
