# PointNet++ Segmentation - PyTorch Implementation

## Results

### Examples from Test Set

:bulb: Notice the convergence in first steps

<table>
    <thead>
        <tr>
            <th style="text-align: center;">Ground Truth</th>
            <th style="text-align: center;">Predicted</th>
            <th style="text-align: center;">Diff.</th>
        </tr>
    </thead>
    <tr>
        <td><img src='images/labeled_0.gif'></td>
        <td><img src='images/predicted_0.gif'></td>
        <td><img src='images/diff_0.gif'></td>
    </tr>
    <tr>
        <td><img src='images/labeled_1.gif'></td>
        <td><img src='images/predicted_1.gif'></td>
        <td><img src='images/diff_1.gif'></td>
    </tr>
    <tr>
        <td><img src='images/labeled_2.gif'></td>
        <td><img src='images/predicted_2.gif'></td>
        <td><img src='images/diff_2.gif'></td>
    </tr>
</table>

### Training Process

![Training Process](images/training.png)

### Accuracy

<table style="text-align: center;">
    <thead>
        <tr>
            <th>Train Set</th>
            <th>Validation Set</th>
            <th>Test Set</th>
        </tr>
    </thead>
    <tr>
        <td>92.22%</td>
        <td>91.59%</td>
        <td>91.73%</td>
    </tr>
</table>

## Resources

- [Qi, C. R., Yi, L., Su, H., & Guibas, L. J. (2017). Pointnet++: Deep hierarchical feature learning on point sets in a metric space. arXiv preprint arXiv:1706.02413.](https://arxiv.org/abs/1706.02413)
- [Pointnet++ Part segmentation](https://github.com/dragonbook/pointnet2-pytorch)
