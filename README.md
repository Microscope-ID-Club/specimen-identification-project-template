# Specimen identification project

This repository was created from the [specimen-identification project template](https://github.com/Microscope-ID-Club/specimen-identification-project-template). It provides a starting structure for a site-based, organisational, or personal trial of conversational specimen examination and identification.

The underlying method is described and versioned separately in [Conversational specimen identification](https://github.com/Microscope-ID-Club/conversational-specimen-identification). Cite the version of that method used by the project; the source repository's all-versions DOI is [10.5281/zenodo.23531039](https://doi.org/10.5281/zenodo.23531039).

## Set up this project

1. Replace this title and introduction with the project's name and purpose.
2. Complete every applicable section of `PROJECT.md` before adding real specimen information.
3. Review the repository visibility and collaborator access settings.
4. Review the local instructions after the managed section of `AGENTS.md` and add only project-specific rules that are necessary.
5. Replace the `Project` value in `templates/specimen-record.md` with the project's preferred name, or leave it as a field to complete for each record.
6. Retain the fictional example or replace it with a clearly labelled fictional or suitably generalised example.
7. Remove this setup checklist when the project documentation is ready for participants.

Creating a repository from this template copies the files but does not subscribe the new project to later improvements. Check the [source method](https://github.com/Microscope-ID-Club/conversational-specimen-identification) periodically. Maintainers with access to the private development package `eco.records` may also use its comparison and synchronization functions for the managed section of `AGENTS.md`.

## Start a specimen record

1. Create a folder under `records/` using a stable identifier, for example `SPECIMEN-001`.
2. Copy `templates/specimen-record.md` into that folder and rename the copy `record.md`.
3. Replace the record identifier in both the metadata and title.
4. Add an `images/` subfolder if supporting photographs are available.
5. Open this repository as the primary local project in the conversational AI system.
6. Ask it to guide the examination according to the project instructions.
7. Review the evolving record and correct anything that does not accurately represent the observations.

## Repository contents

- `AGENTS.md` contains the conversational examination instructions and a local project overlay.
- `PROJECT.md` records the project's scope and governance decisions.
- `METHOD.md` explains the reasoning behind the method.
- `RECORD_FORMAT.md` defines the portable Markdown record format.
- `templates/specimen-record.md` is copied for each specimen.
- `examples/example-specimen.md` is a fictional demonstration.
- `records/` contains project specimen records.

## Licence and attribution

The reusable method and template materials are provided under CC BY 4.0; see `LICENSE.md`. A project must decide and document the access and reuse terms for its own records, images, and local material. The DOI above identifies the source method, not a project created from this template.
