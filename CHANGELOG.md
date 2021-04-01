# Changelog

## 0.8

- [!7](https://gitlab.com/meltano/files-airflow/-/merge_requests/7) Add support for Airflow v2

## 0.7

- [#5](https://gitlab.com/meltano/files-airflow/-/issues/5) Add extractor and loader names as DAG tags

## 0.6

- [#4](https://gitlab.com/meltano/files-airflow/-/issues/4) Use new `meltano schedule run <name>` command

## 0.5

- [#3](https://gitlab.com/meltano/files-airflow/-/issues/3) Fall back on expecting `meltano` to be in PATH if symlink could not be found at `.meltano/run/bin`

## 0.4

- [#2](https://gitlab.com/meltano/files-airflow/-/issues/2) Don't run `meltano elt` again when previous run lasts longer than the interval and hasn't completed yet

## 0.3

- [#1](https://gitlab.com/meltano/files-airflow/-/issues/1) Immediately create DAG for every scheduled pipeline, without waiting until a manual run has succeeded
