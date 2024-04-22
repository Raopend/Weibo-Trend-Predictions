# Weibo-Top-Searches-Predictions
基本统计字段
time: 帖子发布的时间。
count_head: 帖子标题的词数。
count_content: 帖子内容的词数。
avg_word_len: 帖子中单词的平均长度。
参与度与内容质量
r_unique: 内容中不重复词汇的比例。
r_non_stop: 去除停用词后的词汇比例。
r_non_stop_unique: 去除停用词后不重复的词汇比例。
count_link: 帖子中包含的链接数量。
count_inter_link: 帖子中包含的站内链接数量。
count_images: 帖子中包含的图片数量。
count_videos: 帖子中包含的视频数量。
count_labels: 帖子被打的标签数量。
特定论坛分类
forum_life, forum_entertainment, forum_business, forum_stock, forum_tech, forum_international: 分别代表生活、娱乐、商业、股票、技术、国际论坛的帖子计数。
情感分析
total_neutral, sent_total, total_r_pos, total_r_neg: 分别代表情绪中立、总情感得分、正面情感得分、负面情感得分。
r_pos, r_neg: 正面与负面情感的比例。
sent_pos_avg, sent_pos_min, sent_pos_max: 正面情感的平均值、最小值、最大值。
sent_neg_avg, sent_neg_min, sent_neg_max: 负面情感的平均值、最小值、最大值。
head_neutral, sent_head: 标题的中立情感值和总情感得分。
head_neutral_scaled, sent_head_abs: 标题情感的标准化值和绝对值。
引用与影响力
ref_min, ref_max, ref_avg: 引用的最小值、最大值和平均值。
热门标签与评分
worst_label_min, worst_label_max, worst_label_avg: 最差标签的最小值、最大值和平均值。
best_label_min, best_label_max, best_label_avg: 最佳标签的最小值、最大值和平均值。
avg_label_min, avg_label_max, avg_label_avg: 平均标签的最小值、最大值和平均值。
