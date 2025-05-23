# shopstr-hidden-service

## Set-up Instructions

Follow these steps to get the Shopstr Hidden Service running on your local machine:

### 1. Clone the repository

```bash
git clone https://github.com/shopstr-eng/shopstr-hidden-service.git
cd shopstr-hidden-service
```

### 2. Set up the Shopstr repository

```bash
cd shopstr
git init
git remote add origin https://github.com/shopstr-eng/shopstr.git
git fetch
git checkout origin/main -ft
```

### 3. Build and deploy the Hidden Service

```bash
cd ..
bash start.sh
```

### 4. Access the Hidden Service

Once everything is set up, the Hidden Service will be running on the outputted `.onion` address.

Example output: `5ihytfu7tsjjvz4gnqyw55tdloh22nem6hh5psqmojio7vwgu4rtuqyd.onion`

## Update Instructions

Follow these steps to update your deployment to the latest version of Shopstr:

### 1. Pull the latest changes

```bash
cd shopstr-hidden-service
cd shopstr
git pull
```
### 2. Rebuild and redoply the Hidden Service

```bash
cd ..
bash start.sh
```
