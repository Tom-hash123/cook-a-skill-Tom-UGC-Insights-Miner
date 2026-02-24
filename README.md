# UGC Comment Insights Miner
> **Cook A Skill Challenge** — Biến comment threads thành content sections sẵn sàng dùng cho blog.

## Skill làm gì?
Nhận 1+ URL (Reddit, X/Twitter, YouTube, forum, blog) → tự động fetch comments → lọc noise → phân loại insights thành 3 nhóm → phân tích viral patterns → output markdown report sẵn sàng copy-paste vào blog.

## Problem
Content Writer mất 1–2 giờ mỗi bài để tìm và tổng hợp community insights. Hầu hết bỏ qua bước này → bài viết ra generic, không có real human voice, không có E-E-A-T signals → ít được AI search engines (Google SGE, Perplexity) trích dẫn.

## 3 Insight Categories
| Category | Mô tả | SEO/GEO Value |
|---|---|---|
| **Counter-Arguments** | Ý kiến phản biện, góc nhìn khác | Multi-perspective = comprehensive hub |
| **Real-World FAQs** | Câu hỏi thật từ community | Match conversational search + PAA |
| **Personal Experiences** | Case study từ người dùng thật | "Experience" trong E-E-A-T |

## Trước vs. Sau
| Metric | Trước (Manual) | Sau (Có Skill) |
|---|---|---|
| Thời gian | 1–2 giờ | 1–2 phút |
| Comments reviewed | ~30 (lướt) | 100+ (systematic) |
| Viral analysis | Không có | Tự động |

## Cấu trúc Repo
- `SKILL.md` — File instruction chính
- `spec.md` — Spec đã duyệt
- `skill-card.md` — Skill Card 1 trang
- `ai-showcase/`
