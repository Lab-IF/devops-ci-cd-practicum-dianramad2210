# 🔀 Pertemuan 02: Git Advanced - Branching Strategies

## 📋 Tujuan Pembelajaran

Setelah menyelesaikan praktikum ini, mahasiswa mampu:
- Memahami berbagai branching strategies
- Mengimplementasikan GitFlow workflow
- Melakukan merge, rebase, dan resolve conflicts
- Mengelola branch secara efektif

## 📚 Materi

### Branching Strategies

1. **GitFlow** - Feature, develop, release, hotfix branches
2. **GitHub Flow** - Simple feature branch workflow
3. **Trunk-Based Development** - Short-lived feature branches
4. **GitLab Flow** - Environment branches

### GitFlow Branches

```
main (production)     ●───────────────●───────────────●
                       ↑               ↑               ↑
release               ●───────────────●               │
                       ↑                               │
develop     ●─●─●─●─●─●───●─●─●─●─●─●─●───●─●─●─●─●─●
             ↑   ↑       ↑           ↑
feature     ●───●       ●───────────●
```

## 🔧 Tugas Praktikum

### Task 1: Implement GitFlow

1. Initialize repository dengan GitFlow
2. Create feature branch
3. Develop feature dan commit
4. Merge ke develop
5. Create release branch
6. Merge ke main

### Task 2: Resolve Merge Conflicts

1. Create conflicting changes
2. Resolve conflicts manually
3. Document resolution process

## 📤 Submission

```
📁 NIM_Nama_Pertemuan02/
├── 📄 README.md
├── 📁 screenshots/
│   ├── gitflow-branches.png
│   └── merge-conflict-resolution.png
└── 📁 repository-link.txt
```

**Deadline:** Sebelum pertemuan berikutnya