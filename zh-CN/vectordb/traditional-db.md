---
id: traditional-db
title: Traditional database
sidebar_label: Traditional database
---

# 传统数据库与特征向量检索


传统关系型数据库针对字母数字类数据而设计，把不同数据整理归纳为相互关联的集合。但是，由于这类数据库的内建数据并不包括特征向量类型，自然也就没有针对向量的管理和索引方式，而且对于表列数的支持是有限的，所以传统数据库无法支持海量、高维特征向量的存储和搜索。

当然，现在一些传统数据库系统也提供了针对特征向量检索的插件：例如，PostgreSQL的以图搜图插件imgsmlr，和Google的自然语言处理插件word2vector。但是由于这些插件的优化主要基于哈希搜索和一维离散数据搜索，并没有针对高维向量搜索，这些插件虽然能用，但功能不够强大，效率也很低。