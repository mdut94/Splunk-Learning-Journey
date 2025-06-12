# 🔎 SPL Search Queries

## 🔹 Basics
```spl
index=* | stats count by sourcetype
```

## 🔹 Top Hosts
```spl
index=* | top host
```

## 🔹 Timechart Example
```spl
index=* | timechart span=1h count
```

## 📘 Notes
- `stats`: Used for aggregating data
- `top`: Shows most frequent values
- `timechart`: Great for visualizing trends
