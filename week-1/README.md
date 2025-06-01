# Vertex AI Custom Container Prediction Example

This project demonstrates how to use a **custom prediction routine** with **Vertex AI** using a pre-trained model stored in **Google Cloud Storage (GCS)**. The project is structured to run within a **Vertex AI Workbench** notebook environment.

## Project Objective

The objective is to:
- Load a pre-trained `joblib` model from a GCS bucket.
- Perform predictions using a custom container.
- Utilize Vertex AI capabilities without downloading the model locally.

---

## Included Files

### 📄 `SDK_Custom_Container_Prediction.ipynb`
- A Vertex AI Workbench-compatible Jupyter notebook.
- Demonstrates loading the model directly from GCS using `google.cloud.storage` and `joblib`.
- Runs predictions using the loaded model.
- Shows how to interact with GCS using the Python client.


---

## Vertex AI Workbench Setup

| Configuration        | Value                        |
|----------------------|------------------------------|
| Machine type         | `e2-standard-2`              |
| Disk type            | `Standard persistent disk`   |
| Python environment   | Python 3.8+ recommended      |
| Required packages    | `google-cloud-storage`, `joblib`, `scikit-learn` |

### Install dependencies (if not already available):

```bash
pip install google-cloud-storage joblib scikit-learn

