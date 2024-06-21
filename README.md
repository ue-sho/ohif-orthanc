# OHIF-Orchanc

- OHIF
- Orthanc
- PostgreSQL
- S3 (minio)

## How to run

The following command will start two types services: OHIF is activated as a plug-in of Orthanc, and OHIF and Orthanc are activated separately.

```bash
docker compose up -d
```

## Access

Data you uploaded will share between two types services.
The following URLs are the entry points of the services.

- Plugin type:
  - Orthanc: `http://localhost/orthanc-plugin/ui/app/index.html`
  - OHIF: `http://localhost/orthanc-plugin/ohif`
- Separated type:
  - Orthanc: `http://localhost/orthanc-container/ui/app/index.html`
  - OHIF: `http://localhost/ohif`
