# Building forms

Form Builder is a platform/tool for building digital services by representing them as data.

It uses [JSON](glossary#json-and-json-schema) as its data interchange format and [JSON Schema](/glossary#json-schema) to define how to create, validate and process that data.

Form Builder uses [specification data](about-data#specification-data) to create [service data](about-data#service-data) that is used to generate a service that collects [user data](about-data#user-data).

## Specifications and Components

Specifications for components and pages are defined as [JSON schemas](../specifications/schemas.md).

Specifications and components are contained in [fb-components](https://github.com/ministryofjustice/fb-components)

## Editor

The [Editor](editor/editor.md) is an app that provides a UI to build a form (ie. create the necessary data) using the components specified for the form.

## Editor Console

The [Editor Console](editor-console/editor-console.md) is a desktop application that allows users to run copies of the editor locally.