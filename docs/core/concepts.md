# Chroma Core Concepts

## Tenants

A tenant is a logical grouping for a set of databases. A tenant is designed to model a single organization or user. A
tenant can have multiple databases.

## Databases

A database is a logical grouping for a set of collections. A database is designed to model a single application or
project. A database can have multiple collections.

## Collections

Collections are the grouping mechanism for embeddings, documents, and metadata.

## Documents

::: note "Chunks of text"

    Documents in ChromaDB lingo are chunks of text that fits within the embedding model's context window. 
    Unlike other frameworks that use the term "document" to mean a file, 
    ChromaDB uses the term "document" to mean a chunk of text.

Documents are raw chunks of text that are associated with an embedding. Documents are stored in the database and can be
queried for.

## Metadata

Metadata is a dictionary of key-value pairs that can be associated with an embedding. Metadata is stored in the
database and can be queried for.

Metadata values can be of the following types:

- strings
- integers
- floats
- booleans

