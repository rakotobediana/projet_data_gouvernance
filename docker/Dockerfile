#image officielle Data Science
FROM jupyter/scipy-notebook:latest

# Copie des besoins
COPY requirements.txt /tmp/

# Installation des outils de Quality (Sweetviz, Evidently, Drivers SQL)
RUN pip install --quiet --no-cache-dir -r /tmp/requirements.txt

