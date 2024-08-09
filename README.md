# k6 Load test via docker compose

[![k6 load testing](https://github.com/aktech/k6-load-test-docker-compose/actions/workflows/load_test.yml/badge.svg)](https://github.com/aktech/k6-load-test-docker-compose/actions/workflows/load_test.yml)

This is a minimal example to perform load testing with [k6](https://k6.io/) and visualize the results via [xk6-dashboard](https://github.com/grafana/xk6-dashboard).

## 🔨 Usage

```bash
git clone git@github.com:aktech/k6-load-test-docker-compose.git
cd k6-load-test-docker-compose.git
docker compose up
```

Checkout the dashboard at http://localhost:5665/

## ⚙️ Configuration

Modify `script.js` to configure load testing for your use case.

## 📈 Dashboard

<img width="1512" alt="Screenshot 2024-08-09 at 12 54 49 am" src="https://github.com/user-attachments/assets/564fd947-6c0b-4dc1-894e-d1b5e85c23aa">

## LICENSE

Please note that this code is licensed under the [BSD 3-Clause](https://github.com/aktech/k6-load-test-docker-compose/blob/main/LICENSE) license, but k6 itself is licensed under [AGPL-3.0](https://github.com/grafana/k6/blob/869b1683ca6527661640fc9ad7dca1bdfd6224c9/LICENSE.md).
