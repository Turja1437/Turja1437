% Compute the Feigenbaum delta
% Store approximate values in the row vector delta for assessment, where length(delta)= num_doublings and 
% delta(2:num_doublings) are computed from the algorithm described in Lectures 21-23.
num_doublings=11; delta=zeros(1,num_doublings); delta(1)=5;
% Write your code here











% Output your results
fprintf('n        delta(n)\n');
for n=1:num_doublings
    fprintf('%2g %18.15f\n',n,delta(n));
end
