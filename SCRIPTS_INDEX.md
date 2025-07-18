# 📁 脚本索引

本项目包含三个核心脚本文件：

## 🚀 开发脚本

| 脚本 | 用途 | 推荐度 | 端口 | 说明 |
|------|------|--------|------|------|
| `start.sh` | 本地开发服务器 | ⭐⭐⭐⭐⭐ | 3000 | 推荐日常使用 |

## 👀 预览脚本

| 脚本 | 用途 | 端口 | 说明 |
|------|------|------|------|
| `preview.sh` | 本地静态预览 | 8000/8001 | 预览构建后的静态文件 |

## 🌐 发布脚本

| 脚本 | 用途 | 目标 |
|------|------|------|
| `deploy.sh` | GitHub Pages 发布 | `gh-pages` 分支 |

---

## 🎯 快速命令

### 日常开发
```bash
./start.sh
```

### 本地预览
```bash
./preview.sh
```

### 发布到 GitHub Pages
```bash
./deploy.sh
```

---

## 📊 脚本对比

| 特性 | start.sh | preview.sh | deploy.sh |
|------|----------|------------|-----------|
| 环境检查 | ✅ | ✅ | ✅ |
| 自动安装依赖 | ✅ | ❌ | ✅ |
| 缓存清理 | ✅ | ❌ | ✅ |
| 错误处理 | ✅ | ✅ | ✅ |
| 端口管理 | ✅ | ✅ | ❌ |
| 构建功能 | ❌ | ❌ | ✅ |
| 部署功能 | ❌ | ❌ | ✅ |

---

## 🔧 脚本权限

确保所有脚本都有执行权限：

```bash
chmod +x *.sh
```

---

## 📝 使用建议

- **日常开发**: 使用 `start.sh`
- **本地预览**: 使用 `preview.sh`
- **发布部署**: 使用 `deploy.sh` 