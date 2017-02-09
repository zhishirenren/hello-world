# Notes for learning matlab
close all%%
data = load('inputTrainingSet.txt');
fprintf(' x = [%.0f %.0f], y = %.0f \n', [X(1:10,:) y(1:10,:)]');%%
numel（） %%the number of elements
================================plot============================
figure;
plot(1:numel(J_history), J_history, '-b', 'LineWidth', 2);
xlabel('Number of iterations');
ylabel('Cost J');
================================================================
fprintf(' %f \n', theta);%%
pinv(X) inv / \  %%inverse of matrix
A= linspace(-10, 10, 100) %%gengerate 100 numbers between -10 and -10
surf(x , y , z)   %%
xlabel('\theta_0'); ylabel('\theta_1');
@help 'text properties' %% character sequence with symbol;


